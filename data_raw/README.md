# data_raw

Esta carpeta contiene todas las fuentes originales utilizadas en los proyectos.

**Principios**

- Los archivos en esta carpeta no deben modificarse manualmente.
- Representan la versión original descargada o recibida.
- Funcionan como respaldo y punto de partida reproducible.

**Tipos de archivos esperados**
- Shapefiles
- GeoPackages
- CSV
- Excel
- Capas oficiales (INEGI, catastro, transporte, etc.)

**Regla crítica**

Cualquier transformación debe generar un nuevo archivo en data_processed o outputs, nunca sobrescribir aquí.
