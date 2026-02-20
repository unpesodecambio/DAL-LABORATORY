# outputs

Contiene todos los resultados generados por los bloques metodológicos.

Se divide en:

- Capas intermedias
- Resultados finales
- Productos específicos por cliente

**Convención de nombre**

- Formato obligatorio:

  Etapa_DxCyVz_output_#_Descripcion.gpkg

- Ejemplo:

  1_D2C1V1_output_1_Poblacion_total_objetivo.gpkg

**Reglas**

- Cada output debe corresponder a un notebook específico.
- No deben existir archivos sin bloque asociado.
- Los outputs no se editan manualmente.
- Si se requiere ajuste, se modifica el notebook y se genera nueva versión.

**Contenido esperado**

Cada archivo debe contener únicamente:

- ID oficial de manzana
- Variable final limpia o procesada
- Geometría válida
