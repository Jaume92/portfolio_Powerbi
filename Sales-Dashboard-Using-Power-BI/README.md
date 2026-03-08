# Global Sales Business Intelligence Dashboard

Dashboard ejecutivo de ventas construido en Power BI para transformar datos comerciales en decisiones estratégicas: dónde está el margen real, qué segmentos tiran del negocio y dónde se está perdiendo rentabilidad.

---

## El problema que resuelve

Los equipos de dirección y control de gestión necesitan una visión consolidada del negocio que responda rápido a preguntas concretas. Este dashboard está diseñado para eso:

- ¿Estamos por encima o por debajo del margen objetivo este mes?
- ¿Qué segmentos de cliente generan más beneficio real, no solo más facturación?
- ¿Qué productos están arrastrando la rentabilidad hacia abajo?
- ¿Hay estacionalidad en las ventas que debería afectar la planificación?

---

## KPIs principales

| Indicador | Descripción |
|---|---|
| Revenue | Facturación total del periodo |
| Profit | Beneficio neto generado |
| Margin % | Margen de beneficio sobre ventas |
| Average Ticket | Valor medio por pedido |
| Total Orders | Volumen de pedidos en el periodo |

El KPI de margen incluye comparación contra un objetivo de negocio definido (15%) y análisis de tendencia para detectar desviaciones antes de que sean un problema.

---

## Medidas DAX clave
```dax
Profit = SUM(Sales[Profit])

Margin % = DIVIDE([Profit], SUM(Sales[Sales]))

Target Margin = 0.15
```

---

## Visualizaciones incluidas

- Evolución temporal de ventas — para detectar tendencias y estacionalidad
- Profit por segmento de cliente — para separar volumen de rentabilidad real
- Ranking de productos por rentabilidad — para identificar qué productos escalar y cuáles revisar
- Distribución geográfica de ventas — para detectar regiones con mayor y menor aportación
- Distribución de ventas por segmento — para entender la composición del negocio

---

## Proceso de trabajo

**Modelado de datos**

Estructura de datos tipo estrella con tabla de hechos de ventas relacionada con dimensiones de producto, cliente, región y fecha. Tabla calendario creada para análisis temporal correcto.

**Métricas y lógica de negocio**

Medidas DAX para KPIs financieros principales, incluyendo lógica de comparación contra objetivo y cálculo de márgenes por segmento y producto.

**Visualización**

Diseño orientado a reporting ejecutivo: vista general en la página principal con capacidad de drill-down por región, segmento y producto mediante filtros interactivos.

---

## Dataset

Dataset basado en una estructura de ventas tipo retail similar a Superstore, con información de pedidos, productos, segmentos de clientes, fechas, regiones, revenue y profit.

---

## Próximos pasos

- Comparativas Year-over-Year (YoY) para contextualizar el rendimiento actual
- Modelos de forecasting de ventas por región y segmento
- Análisis del impacto de devoluciones en la rentabilidad
- Drill-through por región y categoría de producto

---

Más proyectos: [jaumerrm.dev](https://www.jaumerrm.dev)
