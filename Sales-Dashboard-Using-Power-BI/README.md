Global Sales Business Intelligence Dashboard (Power BI)
Repositorio

git@github.com:Jaume92/portfolio_Powerbi.git

Descripción del Proyecto

Este proyecto consiste en el desarrollo de un dashboard de Business Intelligence orientado a la toma de decisiones ejecutivas utilizando Power BI.

El objetivo principal es transformar datos de ventas en información accionable, permitiendo analizar el rendimiento financiero, la rentabilidad del negocio y el comportamiento por segmentos, productos y regiones.

El dashboard ha sido diseñado siguiendo buenas prácticas de BI corporativo, priorizando métricas clave de negocio y visualizaciones orientadas a análisis estratégico.

Objetivos de Negocio

Monitorizar el rendimiento global del negocio

Evaluar la rentabilidad y eficiencia operativa

Identificar segmentos con mayor y menor aportación al beneficio

Detectar productos más rentables

Analizar tendencias temporales y estacionalidad

Facilitar la toma de decisiones basada en datos

KPIs Principales

El panel principal incluye los siguientes indicadores ejecutivos:

Revenue (Facturación Total)

Profit (Beneficio Neto)

Margin Percentage (Margen de Beneficio)

Average Ticket (Ticket Medio)

Total Orders (Pedidos Totales)

El KPI de margen incluye análisis de tendencia y comparación contra un objetivo de negocio definido.

Visualizaciones Implementadas

El dashboard incluye los siguientes componentes analíticos:

Evolución temporal de ventas

Profit por segmento de cliente

Ranking de productos por rentabilidad

Distribución geográfica de ventas

Distribución de ventas por segmento

Cada visual ha sido diseñado para facilitar una rápida interpretación y extracción de insights.

Medidas DAX Principales
Profit = SUM(Sales[Profit])

Margin % = DIVIDE([Profit], SUM(Sales[Sales]))

Target Margin = 0.15

Herramientas Utilizadas

Power BI Desktop

DAX

Modelado de datos

Visualización de datos

Análisis financiero

Enfoque Business Intelligence

Este proyecto está enfocado en aplicar principios reales de Business Intelligence, incluyendo:

Interpretación de métricas financieras

Optimización de rentabilidad

Análisis basado en KPIs

Reporting ejecutivo

Storytelling con datos

Dataset

Dataset basado en una estructura de ventas tipo retail, similar a Superstore, que incluye información relacionada con:

Pedidos

Productos

Segmentos de clientes

Fechas

Regiones

Revenue y Profit

Posibles Mejoras Futuras

Comparativas Year-over-Year (YoY)

Modelos de forecasting de ventas

Análisis avanzado de márgenes por categoría

Drill-through por región y segmento

Análisis del impacto de devoluciones en la rentabilidad

Autor

Jaume
Business Intelligence y Data Analytics