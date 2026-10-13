# Fácil Reserva • Landing Page Oficial

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/maximartinengo185-ai/facil-reserva-landing)

Landing page moderna, minimalista y responsiva diseñada para promocionar **Fácil Reserva**, la plataforma de gestión de reservas y turnos en tiempo real para negocios independientes.

## 🚀 Despliegue en 1 Clic en Render
Puedes desplegar esta landing page directamente en Render haciendo clic en el botón superior o entrando al siguiente enlace:
👉 **[Desplegar en Render](https://render.com/deploy?repo=https://github.com/maximartinengo185-ai/facil-reserva-landing)**

Render configurará automáticamente el Static Site gracias al archivo `render.yaml` incluido en el repositorio.

---

## 📱 Configuración de WhatsApp
Para cambiar el número de WhatsApp comercial, abre `index.html` y modifica la constante en las líneas iniciales del script:

```javascript
const WHATSAPP_PHONE = "5491123456789"; // Código de país + código de área + número
const WHATSAPP_DEFAULT_MESSAGE = "Hola! Quiero más información sobre Fácil Reserva";
```
Todos los botones de la página se actualizan automáticamente con este número y mensaje.

---

## 🌐 Configuración de Dominio Propio en Render
1. En el panel de Render del sitio, ve a **Settings** > **Custom Domains**.
2. Añade tu dominio (por ejemplo `facilreserva.com` y `www.facilreserva.com`).
3. En tu proveedor de DNS (Cloudflare, DonWeb, etc.):
   - **Para subdominios / www**: Crea un registro `CNAME` apuntando a `facil-reserva.onrender.com`.
   - **Para dominio raíz (@)**: Crea un registro `ALIAS` o `A` con la IP indicada por Render.
4. Render generará automáticamente el certificado SSL (HTTPS) de forma gratuita.
