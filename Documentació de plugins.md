# 📦 Documentació de Plugins del Projecte WordPress

Aquest repositori conté la configuració i els detalls de la pila de plugins utilitzats en aquest lloc web de WordPress.

## 🛠️ Llista de Plugins i Funcionalitats

| Plugin | Categoria | Descripció i Propòsit |
| ----- | ----- | ----- |
| [**Attendant - Free AI Site Search & Chatbot**](https://wordpress.org/plugins/attendant/) | IA i Cerca | Cerca intel·ligent i integració d'un xatbot amb IA per resoldre dubtes dels usuaris i facilitar la navegació. |
| [**bbPress**](https://wordpress.org/plugins/bbpress/) | Comunitat | Motor de fòrums natiu per integrar zones de debat, fils i comunitats dins del lloc web. |
| [**Cookie Bar**](https://wordpress.org/plugins/cookie-bar/) | Legal / Privacitat | Banner informatiu sobre polítiques de galetes per complir amb la normativa de privacitat (RGPD). |
| [**Darkify**](https://wordpress.org/plugins/darkify/) | Accessibilitat / Disseny | Afegeix suport per al **Mode Fosc** (*Dark Mode*) automàtic o activable per l'usuari per millorar l'experiència visual. |
| [**Joinchat - Enhanced "click to chat"**](https://wordpress.org/plugins/creame-whatsapp-me/) | Conversió / Contacte | Botó flotant per iniciar converses de suport o vendes mitjançant WhatsApp o altres aplicacions de missatgeria instantània. |
| [**Loginizer**](https://wordpress.org/plugins/loginizer/) | Seguretat | Protecció del panell d'administració contra atacs de força bruta, limitant i identificant intents fallits d'inici de sessió. |
| [**Pinny's Simple SMTP**](https://wordpress.org/plugins/pinnys-simple-smtp/) | Correu / Infraestructura | Configuració del protocol SMTP per assegurar el lliurament correcte dels correus sortints (evita que caiguin a *Spam*). |
| [**The SEO Framework**](https://wordpress.org/plugins/autodescription/) | Posicionament (SEO) | Plugin lleuger d'optimització per a motors de cerca, automatització de metatags i estructuració de dades en cercadors. |
| [**WP 2FA**](https://wordpress.org/plugins/wp-2fa/) | Seguretat | Implementa l'**autenticació de dos factors (2FA)** per accedir al panell de control, afegint una capa extra de protecció. |
| [**WP Armour - Honeypot Anti Spam**](https://wordpress.org/plugins/honeypot/) | Seguretat / Anti-Spam | Filtre anti-spam transparent per a formularis basat en la tècnica *Honeypot*, evitant l'ús de CAPTCHAs molests. |

## 🔒 Resum de l'Arquitectura de Seguretat

* **Formularis:** Protegits amb `WP Armour` (Honeypot).
* **Accés:** Protegit amb `Loginizer` (bloqueig d'IPs) i `WP 2FA` (segon factor d'autenticació).
* **Lliurament de correu:** Enviaments transaccionals gestionats mitjançant `Pinny's Simple SMTP`.
