# Consultorio Dental Sonrisa Clara

Página de una sola pantalla, pensada para celular, para agendar, confirmar o reprogramar una cita por WhatsApp.

- Sitio estático: un solo archivo, `index.html`. No tiene build ni dependencias.
- Los formularios arman un enlace `wa.me` al 51945738238 con el mensaje ya redactado.
- No guarda datos ni pide DNI, correo o información de salud.

## Publicar en Vercel

1. Sube esta carpeta a un repositorio de GitHub.
2. En Vercel: Add New > Project, elige el repositorio.
3. Framework Preset: Other. Deja vacíos Build Command y Output Directory.
4. Deploy.

## Cambiar el número de WhatsApp

Busca `51945738238` en `index.html` (aparece en los enlaces y en el script) y reemplázalo.
