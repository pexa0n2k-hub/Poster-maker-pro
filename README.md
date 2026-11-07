# POSTER MAKER PRO v2.16 — DISTRIBUCIÓN PRIMERO

- El renderizador PDF/PNG/JPG toma cada hoja desde coordenadas globales del póster.
- Los límites de cada recorte se convierten a píxeles enteros compartidos; los bordes vecinos usan el mismo límite global, evitando redondeos independientes por hoja.
- La posición física en cada página conserva la escala global y el solapamiento configurado/efectivo.
- El fondo blanco de la imagen original se conserva como contenido; las zonas blancas no se tratan como errores.
- Se conserva el diseño Dark Premium Print Studio y las demás funciones de v2.14.

Reemplaza todos los archivos de la raíz de GitHub Pages.
Genera un PDF de prueba y comprueba uniones antes de imprimir el póster completo.


## v2.16
- La pestaña Distribución de hojas aparece primero y abierta al entrar al Diseñador.
- Comparar tamaño queda disponible como segunda pestaña y se abre al seleccionarla.


## v2.17 — Easy Assembly
- Guías opcionales de solapamiento: sombrean las franjas compartidas entre hojas.
- Líneas de corte opcionales: indican el borde de salida derecho e inferior; la hoja siguiente conserva su franja de solape.
- Las ayudas se dibujan sobre cada hoja exportada en PDF, PNG y JPG sin cambiar la geometría ni la escala de los recortes.


## v2.18 — Guía única de solapamiento
Las guías azules se dibujan únicamente en la hoja base (uniones hacia la derecha y hacia abajo). La hoja que se monta encima queda sin rectángulo azul. No se modifican los límites de recorte, la escala ni las líneas de corte.
