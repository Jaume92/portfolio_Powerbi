
# Manufacturing Performance Dashboard — Lean Operations

Dashboard de rendimiento de fabricación construido en Power BI para monitorizar eficiencia productiva, detectar ineficiencias de coste y apoyar iniciativas de mejora continua desde una perspectiva Lean.

---

## El problema que resuelve

En un entorno de fabricación, la diferencia entre producir bien y producir mal se mide en decimales de eficiencia y céntimos por unidad. Este dashboard está diseñado para que un responsable de operaciones pueda detectar rápido dónde están las desviaciones y actuar antes de que se acumulen:

- ¿Estamos por encima o por debajo del objetivo de eficiencia esta semana?
- ¿El coste por unidad está subiendo? ¿En qué productos?
- ¿Qué tipos de producto concentran la mayor parte del coste total?
- ¿Hay variabilidad en producción que indica inestabilidad del proceso?

---

## KPIs principales

| Indicador | Descripción |
|---|---|
| Production Efficiency vs Target | Rendimiento productivo actual comparado con el objetivo operativo definido |
| Coste por unidad | Coste medio de fabricación por unidad producida |
| Producción total | Volumen total producido en el periodo analizado |

---

## Funcionalidades analíticas

- Evolución temporal de producción y costes — para detectar tendencias y variabilidad del proceso
- Análisis Pareto de costes por tipo de producto — para identificar dónde concentrar las acciones de reducción de coste
- Distribución del volumen producido por categoría — para entender la composición del output productivo
- Monitorización de KPIs con objetivos definidos — para detectar desviaciones en tiempo real

---

## Principales conclusiones

- La eficiencia productiva se sitúa por debajo del objetivo definido, lo que indica margen de mejora operativa claro.
- El coste por unidad aumenta de forma correlacionada con los periodos de baja eficiencia — lo que refuerza el argumento para actuar sobre las causas raíz de las desviaciones.
- Un número reducido de productos concentra la mayor parte del coste total, lo que es consistente con la regla 80/20 y permite focalizar acciones.
- La variabilidad en producción y costes sugiere que el proceso no está suficientemente estabilizado — primer paso necesario antes de cualquier iniciativa de mejora continua.

---

## Proceso de trabajo

**Modelado de datos**

Estructuración del modelo con tabla de hechos de producción y dimensiones de producto, categoría y fecha. Tabla calendario para análisis temporal correcto.

**Métricas y lógica operativa**

Medidas DAX para los KPIs principales con lógica de comparación contra objetivo, cálculo de coste por unidad y agrupaciones para el análisis Pareto.

**Visualización**

Diseño orientado a operaciones: vista de KPIs en cabecera con paneles de análisis de tendencia y distribución para drill-down por categoría y periodo.

---

## Archivos del proyecto

- `Jaume_Manufacturing_Performance_Lean.pbix` — Dashboard Power BI
- `README.md` — Documentación del proyecto

---

Más proyectos: [jaumerrm.dev](https://www.jaumerrm.dev)
