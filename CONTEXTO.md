# Contexto — Neoleoneses Inmuebles v0.8.9

## Objetivo
Construir una plataforma inmobiliaria regional centrada en la exploración geográfica de Nuevo León, conectando comunidad y anunciantes con una experiencia clara, transparente y útil.

## Referencias
- Producción: https://neoleoneses-inmuebles.vercel.app/
- Ficha de demostración: https://neoleoneses-inmuebles.vercel.app/?inmueble=0
- Repositorio: https://github.com/rgarzaneoleoneses/neoleoneses-inmuebles
- Copia base: https://neoleoneses-inmuebles.vercel.app/descargas/Neoleoneses_Inmuebles_v0.8.9.zip?v=verified

## Implementación de referencia
HTML, CSS y JavaScript sin framework, contenidos en index.html. Servidor estático; no requiere instalar dependencias para una prueba local. Ejecuta python3 -m http.server 8080 y abre http://localhost:8080/ desde la carpeta raíz. Internet necesario para las teselas de mapa.

500 inmuebles ficticios (350 venta, 150 renta); 51 municipios con geometrías simplificadas de INEGI; 14 imágenes de referencia en dos resoluciones, 28 archivos. Mapa raster OpenStreetMap por defecto, satélite opcional Esri. El recorrido arranca con precarga, vuelo inicial de ~4.6 s y desplazamientos de ~2.6 s; la transición de tarjeta comparte el progreso del giro. Se retiró el sonido por decisión del usuario. Catálogo, filtros, favoritos, panel del entorno simulado, ficha detallada con hasta cinco imágenes ampliables, enlace individual y panel de contacto de ejemplo. WhatsApp permite compartir un mensaje, sin destinatario inmobiliario real.

## Identidad
Paleta base azul noche #030A28, azul #2149FF, azul claro #6F8FFF, blanco; rojo en acciones destacadas, verde para entorno y WhatsApp. Logotipo tipográfico neoleoneses / INMUEBLES procedente de la animación de arranque. Mantener contraste de fichas blancas y mapa azul, diseño adaptado a móviles y mapa como elemento central.

## Límites y pendientes
El sitio es un prototipo estático, no un portal comercial con backend. No tiene datos inmobiliarios, anunciantes ni canales comerciales reales; no incluye autenticación, pagos, sistema de publicación persistente o base de datos. Los lugares cercanos son simulados. Antes del lanzamiento comercial: verificar licencias de cartografía/fotografía, reemplazar datos de ejemplo por registros autorizados, diseñar backend y flujo de publicación, verificar contactos, seguridad y protección de datos. Vercel y GitHub no están configurados para despliegue automático en esta importación.

## Colaboración con ChatGPT
Cada socio conecta su propia cuenta de GitHub y autoriza este repositorio. Pueden pedir: "Lee README.md, AGENTS.md y CONTEXTO.md; analiza index.html, explícame cómo funciona y propón mejoras sin modificar la versión de producción." Para desarrollar, crear una rama, probar, abrir un pull request y coordinar la publicación explícitamente.
