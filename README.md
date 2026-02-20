# Geomarketing Methodology Framework

Este repositorio contiene la arquitectura técnica y metodológica para el desarrollo de proyectos de geomarketing bajo un enfoque modular, reproducible y versionado.

La metodología está estructurada en bloques independientes (Jupyter Notebooks), organizados por etapas del flujo de trabajo:

1. Limpieza de datos
2. Integración de indicadores
3. Filtrado y análisis por dimensión
4. (Futura) construcción de índice ponderado

Cada bloque:
-Tiene múltiples insumos
-Genera un único output formal
-Está versionado mediante Git
-Es reproducible de manera independiente

La unidad espacial base del proyecto es la manzana (salvo casos específicos como movilidad lineal o puntual).

Este repositorio está diseñado para:

-Trabajo colaborativo mediante branches
-Trazabilidad completa de transformaciones
-Separación estricta entre datos crudos, procesados y resultados
-Escalabilidad metodológica
