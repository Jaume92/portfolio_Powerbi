
# Dashboard de Inactividad de Maquinaria — Lean Manufacturing

Análisis de paradas industriales para reducir tiempo de inactividad, priorizar mantenimiento y proteger el rendimiento productivo.

---

## El problema que resuelve

En una planta industrial, cada minuto de parada no planificada tiene un coste directo en producción y capacidad. El reto no es solo registrar las paradas — es entender por qué ocurren, qué máquinas concentran el problema y cuándo actuar antes de que vuelvan a ocurrir.

Este dashboard responde a las preguntas que un responsable de producción o mantenimiento necesita contestar cada semana:

- ¿Qué máquinas paran más y cuál es su impacto real en la línea?
- ¿Las paradas siguen algún patrón temporal que permita anticiparse?
- ¿Las métricas de vibración del husillo están correlacionadas con las incidencias?
- ¿Dónde priorizo el mantenimiento preventivo este mes?

---

## KPIs principales

| Indicador | Descripción |
|---|---|
| Total de paradas | Número de incidencias registradas en el periodo |
| Máquinas analizadas | Equipos incluidos en el análisis |
| Líneas afectadas | Líneas de producción con incidencias registradas |
| Vibración media del husillo | Indicador técnico de estado de los equipos |

---

## Visualizaciones incluidas

- Evolución temporal de paradas — para identificar picos y patrones estacionales
- Ranking de paradas por máquina — para priorizar intervenciones de mantenimiento
- Paradas por línea de producción — para detectar líneas críticas
- Clasificación por tipo de parada — técnicas vs. no técnicas
- Análisis de vibración del husillo por máquina — como indicador de mantenimiento predictivo

---

## Proceso de trabajo

**Preparación de datos**

Limpieza y estandarización de campos, validación de formatos de fecha y métricas técnicas, y creación de tabla calendario para análisis temporal correcto.

**Modelado y métricas**

Construcción de medidas DAX para los KPIs principales, agregaciones personalizadas por máquina, línea y periodo, y optimización del modelo de datos para rendimiento en filtros cruzados.

**Visualización**

Diseño orientado al análisis operativo, con jerarquía de información clara y filtros interactivos por periodo, máquina y línea de producción.

---

## Principales hallazgos

- Existen diferencias significativas en el número de paradas entre máquinas, lo que permite concentrar el mantenimiento donde tiene más impacto.
- Se observa un pico de inactividad durante los meses centrales del periodo analizado, lo que sugiere una posible causa estacional o de carga productiva.
- La vibración del husillo muestra variaciones relevantes entre equipos y puede usarse como indicador preventivo antes de que se produzca la parada.
- Las paradas técnicas representan una parte significativa del impacto total, lo que refuerza el argumento para invertir en mantenimiento predictivo.

---

## Recomendaciones operativas

- Priorizar mantenimiento preventivo en las máquinas con mayor concentración de incidencias.
- Investigar las causas detrás del pico de paradas en los meses centrales del periodo.
- Incorporar métricas de vibración y presión como base para un modelo de mantenimiento predictivo.
- Implementar seguimiento continuo mediante paneles operativos actualizados en tiempo real.

---

## Archivos del proyecto

- `manufacturing_downtime_jaume.pbix` — Dashboard Power BI
- `Machine Downtime.csv` — Dataset utilizado

---

## Nota

El dataset corresponde a datos industriales simulados con fines formativos y de demostración analítica.

Este proyecto forma parte de un portfolio enfocado en Business Intelligence, Data Analytics y Digitalización Industrial.

Más proyectos: [jaumerrm.dev](https://www.jaumerrm.dev)
Autor

Jaume
Área de enfoque: Business Intelligence y Analítica Operativa
