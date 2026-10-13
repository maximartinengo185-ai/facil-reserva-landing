# Fácil Reserva • Landing Page Oficial

Landing page moderna, minimalista y responsiva diseñada para promocionar **Fácil Reserva**, la plataforma de gestión de reservas y turnos en tiempo real para negocios independientes.

## 🚀 Características
- **Mobile-First & Ultraligera**: Construida en HTML5 semántico con Tailwind CSS y Google Fonts. Sin dependencias pesadas de servidor.
- **Enfocada en Conversión (CRO)**: Estructura probada para captación directa a WhatsApp.
- **Mockup Dual Interactivo**: Representación esquemática sincronizada de la web de clientes y la app móvil de administración.
- **Secciones incluidas**:
  - Hero con propuesta de valor y mockup en vivo.
  - ¿Cómo Funciona? (3 pasos sencillos).
  - Rubros compatibles (Deportes, gimnasios, estética, consultorios).
  - Beneficios clave y tabla comparativa "Antes vs Con Fácil Reserva".
  - Acordeón interactivo de Preguntas Frecuentes (FAQ).
  - Call to action de cierre y botón flotante permanente de WhatsApp con pulso.

## 📱 Configuración de WhatsApp
Para cambiar el número de WhatsApp comercial, abre `index.html` y modifica la constante en las líneas iniciales del script:

```javascript
const WHATSAPP_PHONE = "5491123456789"; // Código de país + código de área + número
const WHATSAPP_DEFAULT_MESSAGE = "Hola! Quiero más información sobre Fácil Reserva";
```
Todos los botones de la página se actualizan automáticamente con este número y mensaje.

## 🌐 Despliegue en Render (Static Site)
1. Conecta tu repositorio de GitHub en [dashboard.render.com](https://dashboard.render.com).
2. Selecciona **New +** -> **Static Site**.
3. Configuración:
   - **Build Command**: *(dejar vacío)*
   - **Publish Directory**: `.`
4. ¡Listo! Render desplegará tu landing con CDN global y certificado SSL (HTTPS) gratuito.
