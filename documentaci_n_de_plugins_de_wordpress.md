# 📦 Documentación de Plugins del Proyecto WordPress

Este repositorio contiene la configuración y detalles de la pila de plugins utilizados en este sitio web de WordPress.

---

## 🛠️ Lista de Plugins y Funcionalidades

| Plugin | Categoría | Descripción y Propósito |
| :--- | :--- | :--- |
| **Attendant - Free AI Site Search & Chatbot** | IA y Búsqueda | Búsqueda inteligente e integración de un chatbot con IA para responder dudas de los usuarios y facilitar la navegación. |
| **bbPress** | Comunidad | Motor de foros nativo para integrar zonas de debate, hilos y comunidades dentro del sitio web. |
| **Cookie Bar** | Legal / Privacidad | Banner informativo sobre políticas de cookies para cumplir con las normativas de privacidad (RGPD). |
| **Darkify** | Accesibilidad / Diseño | Añade soporte para **Modo Oscuro** (*Dark Mode*) automático o ejecutable por el usuario para mejorar la experiencia visual. |
| **Joinchat - Enhanced "click to chat"** | Conversión / Contacto | Botón flotante para iniciar conversaciones de soporte o ventas vía WhatsApp u otras apps de mensajería instantánea. |
| **Loginizer** | Seguretat | Protección del panel de administración frente a ataques de fuerza bruta, limitando e identificando intentos fallidos de inicio de sesión. |
| **Pinny's Simple SMTP** | Correo / Infraestructura | Configuración del protocolo SMTP para asegurar la correcta entrega de correos salientes (evita que caigan en *Spam*). |
| **The SEO Framework** | Posicionamiento (SEO) | Plugin ligero de optimización para motores de búsqueda, automatización de metatags y estructuración de datos en buscadores. |
| **WP 2FA** | Seguridad | Implementa la **autenticación de dos factores (2FA)** para acceder al panel de control, añadiendo una capa extra de protección. |
| **WP Armour - Honeypot Anti Spam** | Seguridad / Anti-Spam | Filtro anti-spam transparente para formularios basado en la técnica *Honeypot*, evitando el uso de CAPTCHAs molestos. |

---

## 🔒 Resumen de Arquitectura de Seguridad

* **Formularios:** Protegidos con `WP Armour` (Honeypot).
* **Acceso:** Protegido con `Loginizer` (bloqueo de IP) y `WP 2FA` (segundo factor de autenticación).
* **Entregabilidad:** Envíos transaccionales gestionados vía `Pinny's Simple SMTP`.