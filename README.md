# Sitio web personal — Andrés Camilo Osorio Sánchez

Sitio estático, responsive y sin dependencias de JavaScript. Está construido con HTML, CSS y JavaScript nativos para facilitar su integración en cualquier hosting o servidor web.

## Archivos
- `index.html`: estructura, contenido, metadatos SEO y enlaces de contacto.
- `styles.css`: diseño visual adaptable a móviles, tabletas y escritorio.
- `script.js`: menú móvil, navegación activa, animaciones de entrada y año automático.

## Publicación
1. Descomprime el paquete.
2. Sube `index.html`, `styles.css` y `script.js` a la carpeta pública de tu hosting (por ejemplo, `public_html/` o la raíz de tu sitio).
3. Abre el dominio y verifica los enlaces de correo y teléfono.

No requiere Node, compilación, base de datos ni instalación de paquetes. La tipografía se carga desde Google Fonts; si prefieres no depender de un servicio externo, elimina los dos `preconnect` y el enlace de Google Fonts en `index.html` y se utilizarán las fuentes de respaldo.

## Personalización antes de producción
- Revisa que los correos y el teléfono publicados sean los que deseas hacer públicos.
- Añade una fotografía profesional si lo deseas. El diseño actual utiliza una composición gráfica abstracta y no presupone una fotografía.
- El CV suministrado no registra experiencia empresarial específica. Por rigor, el sitio presenta la dirección académica y la experiencia en medios como trayectoria profesional, sin atribuir cargos empresariales no documentados.
- Se recomienda añadir dominio propio, favicon, imagen social Open Graph y una política de privacidad si posteriormente se incorporan formularios o analítica.

## Accesibilidad y rendimiento
Incluye estructura semántica, enlace para saltar al contenido, navegación etiquetada, estados del menú móvil, enlaces externos seguros y respeto por `prefers-reduced-motion`.
