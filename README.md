# Mi semana

Planner semanal interactivo (4:00 – 23:00): bloques con duración libre que reacomodan el resto del día, clases fijas, pendientes, sueño automático y exportación a imagen/PDF.

Sitio estático (un solo `index.html`), sin build. En Vercel: **Framework Preset: Other**, sin comandos.

Al abrirla pide perfil: **Aarón** (con su horario) o **Luis** (en blanco). Cada perfil guarda lo suyo por separado.

Los datos se guardan en el navegador (localStorage). Para pasarlos a otro dispositivo: **⋯ Más → Descargar respaldo** y luego **Importar archivo** en el otro.

## App en el celular

Es una PWA: en **Android (Chrome)** sale "Instalar app"; en **iPhone (Safari)** botón Compartir → **Agregar a inicio**. Funciona sin internet gracias a `sw.js`.
