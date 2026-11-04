# POSTER MAKER PRO v2.15 — CONTINUIDAD DE RECORTES

- El renderizador PDF/PNG/JPG toma cada hoja desde coordenadas globales del póster.
- Los límites de cada recorte se convierten a píxeles enteros compartidos; los bordes vecinos usan el mismo límite global, evitando redondeos independientes por hoja.
- La posición física en cada página conserva la escala global y el solapamiento configurado/efectivo.
- El fondo blanco de la imagen original se conserva como contenido; las zonas blancas no se tratan como errores.
- Se conserva el diseño Dark Premium Print Studio y las demás funciones de v2.14.

Reemplaza todos los archivos de la raíz de GitHub Pages.
Genera un PDF de prueba y comprueba uniones antes de imprimir el póster completo.
