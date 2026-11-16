# Senda — web animada

Web responsive mobile first para descubrir rutas de naturaleza. Proyecto realizado con HTML semántico y CSS propio; no necesita JavaScript.

## Estructura

- `index.html`: portada y propuesta del servicio.
- `rutas.html`: selección de rutas, favoritos, tarjeta 3D y preguntas frecuentes.
- `movimiento.html`: guía de tokens, inventario de animaciones y decisiones de accesibilidad y rendimiento.
- `css/estilos.css`: diseño, componentes y responsive.
- `css/animaciones.css`: tokens, transiciones, keyframes, movimiento reducido y apariciones con scroll timelines CSS. Sin soporte para esa función, el contenido sigue visible.
- `capturas/`: capturas de la portada a 360, 768 y 1280 px, más una captura con movimiento reducido.
- `grabaciones/`: GIFs breves de la entrada de portada, el menú, la aparición al desplazarse y movimiento reducido.

## Probar localmente

Abre `index.html` en un navegador moderno o sirve esta carpeta con cualquier servidor estático. No se requieren dependencias ni compilación.

## Publicación pendiente

Las evidencias incluidas se capturaron en navegador. La publicación en GitHub Pages y la incorporación al portfolio del Tema 06 requieren el repositorio y el portfolio del alumno; este directorio no está conectado a una cuenta de publicación.

## Accesibilidad

Las páginas respetan `prefers-reduced-motion`, funcionan sin JavaScript, proporcionan foco visible, usan controles nativos y evitan depender exclusivamente del color para comunicar estados.
