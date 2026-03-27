# bda-modulo-3-analisis-clientes-sanchocotanda

Autora: María Sancho

Este es un proyecto educativo basado en la limpieza, exploración, análisis y visualización de datos a partir de varios archivos CSV. Su objetivo es ofrecer una práctica integral del flujo de trabajo de datos. Permite aprender a limpiar y preparar datos, explorar su estructura y características, analizar patrones mediante estadísticas descriptivas y visualizar información relevante, así como tomar decisiones sobre la gestión de los datos.

## Funcionalidades del proyecto

El proyecto permite:

- **Cargar y explorar** datos de clientes y actividades de vuelo desde archivos CSV.
- **Limpiar y transformar** los datos eliminando duplicados y ajustando formatos.
- **Unir** distintos datasets para obtener una visión completa del comportamiento de los clientes.
- **Analizar** variables categóricas y numéricas: distribución, cuartiles, percentiles, desviación estándar, coeficiente de variación.
- **Visualizar** los datos mediante gráficos de barras, dispersión y otras representaciones.
- **Explorar** intersecciones de grupos de clientes, como los que se unieron mediante promociones y los que cancelaron en un mismo año.

## Técnicas y conceptos aplicados
- Manipulación de datos con Pandas: selección de columnas, filtrado, unique, value_counts, agrupaciones (groupby) y agregaciones.
- Limpieza y preparación de datos: eliminación de duplicados, renombrado de columnas, conversión de tipos de datos y gestion de nulos.
- Estadística descriptiva: media, mediana, desviación estándar (std), rango, cuartiles, percentiles, coeficiente de variación (coef_var).
- Visualización de datos con Matplotlib y Seaborn:
- Gráficos de barras y de dispersión.
- Personalización: figsize, xticks, rotation, alpha, grid.
- Conjuntos y operaciones con set para identificar intersecciones entre grupos de clientes.


## Contenido del repositorio

El repositorio contiene los siguientes documentos:

1. **Notas sobre los documentos:** archivo .txt con observaciones iniciales sobre los CSV originales y la estructura de los datos.

2. **CSV originales:**
- customer_Flight_activities.csv
- customer_loyalty_history.csv
3. **CSV limpios:**
- df_activity_clean.csv
- df_history_clean.csv
4. **CSV limpios unidos:** combinación de los .csv limpios para análisis integrales = documentos_unidos.csv

5. **Ejercicios en Jupyter Notebook:**
- ejercicio_fase_1.ipynb
- ejercicio_fase_2.ipynb
- ejercicio_fase_3_y_4.ipynb
6. **Este README:** resumen del proyecto, técnicas utilizadas y contenidos del repositorio.

**Nota:** Esta es una práctica académica. Verás que está repleta de notas para mi propio aprendizaje y, por supuesto, para ayudarte a ti si las necesitas. Es posible que algunas decisiones, graficos o comprobaciones no tengan sentido, se han ejecutado con fines educativos y como práctica.

Gracias por leer este README :)