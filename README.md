# Inventario del taller

App web instalable (Android) para el inventario del taller: retales y tableros, madera maciza, muebles desarmados y armados, tejas, herrajes, pinturas y metales. Funciona sin internet; los datos viven en el celular (IndexedDB).

- Buscar retal por medida mínima (gira la pieza).
- Muebles desarmados con despiece: marca qué piezas faltan.
- Valor de cada ítem con precios de referencia (IVA, fuente y fecha); cruce con el respaldo de la app Proveedores.
- Salidas a obra y cortes parciales con valor cargado al proyecto.
- Etiquetas QR en hoja carta (3 × 10) y lector QR dentro de la app.
- Buzón de Claude: cargas cifradas en `buzon/` (ver `herramientas/buzon.py`). La clave nunca va en el repositorio.
