# POSTER MAKER PRO

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `manifest.webmanifest` y `sw.js` a la raíz.
3. En Settings → Pages, selecciona Deploy from a branch, `main` y `/root`.
4. Abre la URL publicada en Chrome Android y usa “Añadir a pantalla de inicio”.

## Uso
- Sube una imagen JPG, PNG o WEBP.
- Define el tamaño final en centímetros.
- Elige papel, orientación, margen y solapamiento.
- Usa división automática o define filas y columnas manualmente.
- Descarga PDF o las hojas como PNG/JPG.

## Impresión
En el diálogo de impresión selecciona tamaño real / 100%, sin “ajustar a página”.
Haz primero una prueba con una hoja para comprobar márgenes y escala.

## Nota técnica
El generador PDF usa jsPDF desde CDN, por lo que requiere conexión a internet para cargar esa biblioteca. El resto del procesamiento de imagen se realiza en el navegador.
