# Análisis de Siniestros Viales en Buenos Aires

## Descripción del Proyecto

Este proyecto se sitúa en el rol de un Data Analyst con el objetivo de analizar los siniestros viales ocurridos en la Ciudad de Buenos Aires durante el periodo 2016-2021. El análisis tiene como fin generar información valiosa que permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales en estos incidentes.

## Contexto del Problema

Los siniestros viales, también conocidos como accidentes de tráfico, son eventos que involucran vehículos en las vías públicas y pueden tener diversas causas. En la Ciudad de Buenos Aires, el alto volumen de tráfico y la densidad poblacional agravan el problema, afectando la seguridad de residentes y visitantes. La prevención de siniestros viales requiere educación vial, cumplimiento de normas de tráfico, infraestructuras seguras y la promoción de vehículos más seguros.

## Datos del Proyecto

El dataset usado fue proporcionado por el Observatorio de Movilidad y Seguridad Vial (OMSV) y contiene información sobre homicidios en siniestros viales acaecidos en Buenos Aires. Está compuesto por dos hojas: `hechos` y `víctimas`, y también incluye diccionarios de datos para un mejor entendimiento.

## Metodología

Se aplicaron diversas técnicas y herramientas para realizar el análisis exploratorio de datos (EDA), construir un dashboard interactivo y definir KPIs relevantes.

### Tecnologías y Herramientas Utilizadas

- **Python**: Para la limpieza de datos y el análisis exploratorio.
- **Pandas y Numpy**: Para manipulación y análisis de datos.
- **Matplotlib/Seaborn**: Para la creación de gráficos y visualización de datos.
- **Power BI**: Para la creación del dashboard interactivo.
- **Jupyter Notebook**: Para documentar el proceso de análisis.
- **Google Maps**: Para la corrección manual de coordenadas.

### Procesamiento de Datos

1. **Carga y Limpieza de Datos**: Los datos fueron cargados y se realizaron operaciones de limpieza, incluyendo la eliminación de duplicados y la imputación de valores faltantes.
2. **Análisis Exploratorio de Datos (EDA)**: Se analizaron los datos para identificar patrones y tendencias, y se documentaron los hallazgos utilizando gráficos y visualizaciones.
3. **Construcción del Dashboard**: Se creó un dashboard en Power BI para facilitar la exploración interactiva de los datos y la interpretación de la información.
4. **Definición de KPIs**: Se definieron y midieron los KPIs propuestos, así como un KPI adicional relevante para la temática.

### Proyecto Estructura

- **Data**:
  - `.csv` files with received data (`DB_seed`), transformed data (`_ETL`), and additional data for EDA.
- **Notebooks**:
  - Jupyter notebooks for ETL, EDA, and supplementary analysis.
- **Dashboard**:
  - Power BI file with the interactive dashboard.
- **README.md**:
  - Detailed project description and guide.

### Análisis y Conclusiones

Se identificaron los patrones más comunes en los siniestros viales, incluyendo las ubicaciones y horas más peligrosas, así como los tipos de vehículos más involucrados. Las conclusiones extraídas del análisis proporcionan información valiosa para implementar políticas de seguridad vial más efectivas en Buenos Aires.

### Desafíos y Mejoras Futuras

1. **Base de Datos en SQL**: Crear una base de datos en un motor SQL y utilizarla como fuente de datos para Power BI.
2. **Ejecución de Scripts de Python**: Ejecutar scripts de Python directamente en Power BI para análisis más complejos.
3. **Cruce de Datos**: Integrar datasets adicionales para enriquecer el análisis y comparar información disponible.

## Fuentes de Datos

- [Buenos Aires Data](https://docs.google.com/spreadsheets/d/1nq00jGIZHQ1RLSET43zKnUsMsoFb-pBg/edit#gid=1625530738)
- [Diccionario de Data](https://docs.google.com/spreadsheets/d/1Op98U-Hh2a3Q7uuznAzdl4Bf8r8qPr4m/edit#gid=1771770012)
- [Comunas de CABA](https://data.buenosaires.gob.ar/dataset/comunas)

Recordamos por último que este proyecto tiene únicamente fines educativos, así que no debe ser utilizado para tomas de decisiones reales de seguridad vial en la Ciudad de Buenos Aires ni en otra localidad. ¡Gracias por su atención!
