# Punto Cero Logistica

Sitio estático de Punto Cero Logistica.

## Antes de publicar

- Crea un formulario en Formspree y pega su URL pública (`https://formspree.io/f/...`) en `CONFIG.formEndpoint` al final de `index.html`. Completa también `CONFIG.privacyContact` y `CONFIG.privacyAddress`, actualiza `aviso-privacidad.html` y cambia `CONFIG.privacyNoticeReady` a `true`; hasta entonces, el formulario permanece oculto.
- El sitio ya resuelve `og:image`, `og:url`, `canonical` y `twitter:image` dinámicamente con la URL actual del dominio, así que no requiere cambiar el dominio para que el preview funcione en preproducción. Cuando se publique el dominio final, el contenido SEO se ajustará automáticamente.
- Completa el aviso de privacidad con el domicilio legal, el correo para solicitudes sobre datos, los plazos de conservación y las transferencias aplicables antes de habilitar la recolección de datos.
