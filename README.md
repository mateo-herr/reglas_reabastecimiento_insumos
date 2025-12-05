# Reglas de Reabastecimiento de Insumos

Este proyecto contiene un análisis de datos históricos de compras para definir políticas óptimas de reabastecimiento de insumos de producción.

## Descripción

El notebook principal `regla de reabastecimiento de insumos.ipynb` procesa el histórico de movimientos y clasifica los insumos utilizando una metodología multidimensional:

*   **Clasificación ABC (Volumen):** Basada en el consumo normalizado por familias.
*   **Clasificación XYZ (Frecuencia):** Basada en la regularidad del consumo semanal.

## Resultados

El análisis genera un reporte HTML (`reporte_reabastecimiento.html`) que incluye:
*   Dashboard ejecutivo.
*   Matrices estratégicas.
*   Tabla detallada con parámetros de reabastecimiento (ROP, Stock de Seguridad) para cada insumo.

## Estructura

*   `regla de reabastecimiento de insumos.ipynb`: Código fuente del análisis.
*   `PRODUCCION.xlsx`: Fuente de datos (Ignorado en el repositorio por confidencialidad).
