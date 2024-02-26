
---

# Resumen del Análisis de la Base de Datos "valuacion_mkt_campaign"

## Descripción del Problema
El área de marketing de una empresa desea generar una clusterización para poder tener mayor éxito con sus campañas. Se proporcionó una base de datos que contiene información sobre clientes, incluyendo características demográficas y comportamiento de compra.

## Procesamiento de Datos
1. **Carga de Datos:** Se cargaron los datos desde el archivo CSV "valuacion_mkt_campaign.csv".
2. **Selección de Características:** Se seleccionaron las columnas relevantes para el análisis, incluyendo la edad, antigüedad, ingreso, recencia de compra y gastos en diferentes categorías de productos.
3. **Estandarización de Datos:** Los datos fueron estandarizados para asegurar que todas las características tuvieran la misma escala y contribución al análisis.

## Análisis de Clústeres
### Búsqueda de Anomalías
- Se identificaron y descartaron registros anómalos correspondientes al 5% de la muestra, utilizando las columnas de comportamiento de compra.

### Feature Extraction
- Se redujo el número de variables utilizando un método de extracción de características, buscando una representación que explicara el 90% de la varianza original de los datos.

### Clustering
- Se utilizó el algoritmo K-Means para clusterizar el comportamiento de los clientes.
- Se determinó el número óptimo de clústeres que no excediera los 8, considerando las restricciones de la empresa de marketing.

## Resultados
- Se generaron clústeres que agrupan a los clientes según sus características demográficas y comportamiento de compra.
- Se identificaron patrones claros de comportamiento dentro de cada clúster, lo que proporciona información valiosa para personalizar las estrategias de marketing.
- Se calcularon y graficaron los centroides de cada clúster para visualizar la ubicación media de los clientes en el espacio de características.

## Conclusiones
El análisis de clústeres permitió identificar segmentos de clientes con características similares, lo que puede ayudar a la empresa de marketing a personalizar sus estrategias y campañas para satisfacer las necesidades específicas de cada grupo. Estos hallazgos proporcionan información valiosa para mejorar la efectividad y el rendimiento de las campañas de marketing.

---