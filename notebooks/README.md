# notebooks

Esta carpeta contiene los bloques operativos de la metodología.

Cada archivo .ipynb representa una unidad funcional del flujo de trabajo.

**Convención de nombre**

- Formato obligatorio:

  Etapa_DxCyVz_Descripcion.ipynb
- Ejemplo:

  1_D2C1V1_Poblacion_total_objetivo.ipynb

Donde:

- Etapa → 1 (Limpieza), 2 (Integración), 3 (Análisis)
- Dx → Dimensión
- Cy → Categoría
- Vz → Variable

**Estructura interna obligatoria**

Cada notebook debe incluir:

1. Identificación del bloque
2. Objetivo
3. Inputs
4. Procesos realizados
5. Validaciones
6. Output generado

**Principios**

- Un bloque = un output principal
- No se mezclan variables distintas en un mismo notebook
- Todo output debe poder reproducirse desde cero
- Toda transformación debe estar documentada en Markdown
