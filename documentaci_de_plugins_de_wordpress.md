# 📦 Documentació de Plugins del Projecte WordPress

Aquest repositori conté la configuració i els detalls de la pila de plugins utilitzats en aquest lloc web de WordPress.

## 🛠️ Llista de Plugins i Funcionalitats

| Plugin | Categoria | Descripció i Propòsit |
| ----- | ----- | ----- |
| **Attendant - Free AI Site Search & Chatbot** | IA i Cerca | Cerca intel·ligent i integració d'un xatbot amb IA per resoldre dubtes dels usuaris i facilitar la navegació. |
| **bbPress** | Comunitat | Motor de fòrums natiu per integrar zones de debat, fils i comunitats dins del lloc web. |
| **Cookie Bar** | Legal / Privacitat | Banner informatiu sobre polítiques de galetes per complir amb la normativa de privacitat (RGPD). |
| **Darkify** | Accessibilitat / Disseny | Afegeix suport per al **Mode Fosc** (*Dark Mode*) automàtic o activable per l'usuari per millorar l'experiència visual. |
| **Joinchat - Enhanced "click to chat"** | Conversió / Contacte | Botó flotant per iniciar converses de suport o vendes mitjançant WhatsApp o altres aplicacions de missatgeria instantània. |
| **Loginizer** | Seguretat | Protecció del panell d'administració contra atacs de força bruta, limitant i identificant intents fallits d'inici de sessió. |
| **Pinny's Simple SMTP** | Correu / Infraestructura | Configuració del protocol SMTP per assegurar el lliurament correcte dels correus sortints (evita que caiguin a *Spam*). |
| **The SEO Framework** | Posicionament (SEO) | Plugin lleuger d'optimització per a motors de cerca, automatització de metatags i estructuració de dades en cercadors. |
| **WP 2FA** | Seguretat | Implementa l'**autenticació de dos factors (2FA)** per accedir al panell de control, afegint una capa extra de protecció. |
| **WP Armour - Honeypot Anti Spam** | Seguretat / Anti-Spam | Filtre anti-spam transparent per a formularis basat en la tècnica *Honeypot*, evitant l'ús de CAPTCHAs molests. |

## 🔒 Resum de l'Arquitectura de Seguretat

* **Formularis:** Protegits amb `WP Armour` (Honeypot).
* **Accés:** Protegit amb `Loginizer` (bloqueig d'IPs) i `WP 2FA` (segon factor d'autenticació).
* **Lliurament de correu:** Enviaments transaccionals gestionats mitjançant `Pinny's Simple SMTP`.