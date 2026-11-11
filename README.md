# Luxury CK Design · Vista del diseño y «Diseña tu cocina»

Páginas públicas que abren los QR y links que genera la app **Luxury Design**.

- `index.html` (español) y `en/index.html` (inglés): la vista del cliente y del instalador. El diseño viaja dentro
  del link (después de `#d=`), comprimido; esta página no guarda ni recibe datos de ningún servidor.
- `disena/index.html` (español) y `en/disena/index.html` (inglés): «Diseña tu cocina», para que el cliente diseñe su
  cocina (y closet, coffee station, cocina exterior, baño, baño master, laundry o pared / TV) y la mande al taller.
  Lo que manda va cifrado de punta a punta: solo lo abren la app del taller y el navegador del cliente. Esta página
  no lleva precios ni llaves: los precios y la llave pública del taller vienen en el link del QR.
- No se edita a mano: se genera desde el repo `Luxury-design` con `npm run viewer`, que escribe la carpeta `site/`,
  y se copia aquí.
