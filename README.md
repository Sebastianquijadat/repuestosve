# RepuestosVE

Prototipo de una sola página para un marketplace venezolano de compra y venta de repuestos de vehículos.

- HTML + Tailwind CSS (CDN) + JavaScript sin dependencias.
- Precios en US$ con referencia en Bs. (tasa simulada).
- Buscador, filtro por categoría y selector Marca > Modelo > Año.
- Envíos por MRW, Zoom y Tealca; pagos por Pago Móvil, Zelle, Efectivo, Transferencia nacional y Binance.

## Cómo verlo

Abre `repuestosve.html` en el navegador (necesita internet para cargar Tailwind y la fuente). La carpeta `img/` tiene que quedar al lado del HTML.

## Fotos

Las 8 fotos de `img/` son fotos reales de Wikimedia Commons (licencias CC BY, CC BY-SA y dominio público), recortadas y convertidas a WebP. Las licencias exigen dar crédito: el autor, la licencia y el enlace de cada foto están en el campo `photo` de cada publicación en `LISTINGS` y se muestran en el pie de la página. Si una foto no carga, la tarjeta vuelve a mostrar el dibujo de la pieza.

## Datos de ejemplo por reemplazar

- Tasa de cambio (`RATE`, `RATE_DATE`).
- Las 8 publicaciones (`LISTINGS`) y sus fotos en `img/`.
- WhatsApp de atención y enlaces legales del pie de página.

`.taste-skill/app/direction.json` guarda el estilo visual generado con taste-skill (framed-sheet).
