FOTOS REALES DE LOS AUTOS PARA LA DEMO

Para que la demo muestre fotos reales en lugar del CDN automático,
poné acá las imágenes con estos nombres exactos:

  car-1.jpg → Ford Ranger XL 2019 (blanca)
  car-2.jpg → Volkswagen Amarok V6 2018 (gris)
  car-3.jpg → Toyota Hilux SR 2020 (negra)
  car-4.jpg → Chevrolet Onix LT 2021 (roja)
  car-5.jpg → Ford Focus SE 2016 (azul)
  car-6.jpg → Renault Kangoo Express 2018 (blanca)

RECOMENDACIONES

- Formato: JPG (peso bajo) o PNG.
- Tamaño ideal: 800x500 px aprox. (3:2 horizontal).
- Encuadre: el auto centrado, lateral o 3/4. Fondo neutro queda mejor.
- Peso por foto: idealmente <150 KB.

ORDEN DE CARGA (cómo decide la demo qué mostrar)

1. Si el archivo ./cars/car-{N}.jpg existe → lo usa.
2. Si no, intenta el CDN público de imagin.studio (renders por marca/modelo/año).
3. Si tampoco, muestra la silueta SVG como fallback.

DÓNDE SACAR FOTOS RÁPIDO

- Tus propios autos (lo ideal).
- Fotos de venta en Marketplace / OLX / Mercado Libre del mismo modelo.
- Wikipedia / Wikimedia Commons (licencia libre).
- Unsplash / Pexels (gratis, sin atribución).

Después de subir las fotos, hacé git add + commit + push y Vercel
re-deploya solo.
