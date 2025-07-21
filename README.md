# AnalisisApss
Este repositorio contiene un análisis exhaustivo de datos de aplicaciones móviles, utilizando datasets de Google Play Store y Apple App Store. El objetivo principal es extraer información valiosa sobre el rendimiento, la popularidad, la monetización y las características de las aplicaciones en ambos ecosistemas.

Contenido del Repositorio
notebooks/: Directorios que contienen los notebooks de Jupyter para cada análisis.

google_play_analysis.ipynb: Análisis de datos de la Google Play Store.

apple_app_store_analysis.ipynb: Análisis de datos de la Apple App Store.

data/: Directorio donde se almacenan los datasets originales y procesados.

googleplaystore.csv

AppleStore.csv

(Posibles archivos .csv o .xlsx de datos limpios si se guardaron)

reports/: (Opcional) Directorio para informes o resúmenes en PDF/HTML de los hallazgos clave.

visualizations/: (Opcional) Directorio para gráficos y visualizaciones exportadas.

Preguntas de Investigación / Objetivos del Análisis
Este proyecto busca responder a preguntas como:

¿Cuáles son las aplicaciones más populares (por descargas/calificaciones) en cada tienda?

¿Cómo se distribuyen los ratings y las calificaciones en ambos mercados?

¿Existe una correlación entre el precio de una aplicación y su popularidad o calificación?

¿Cómo influye el tamaño de la aplicación en su adopción y calificación?

¿Qué géneros/categorías dominan en cada tienda y cómo se diferencian en términos de monetización y calidad?

¿Cómo afecta la frecuencia de actualización o la antigüedad de una aplicación a su rendimiento?

¿Qué impacto tienen características como el número de idiomas soportados o el soporte a dispositivos en la popularidad de las aplicaciones?

Comparación de tendencias y características entre la Google Play Store y la Apple App Store.

Metodología
El análisis se llevó a cabo utilizando Python 3 y las siguientes librerías principales:

pandas: Para la manipulación y análisis de datos.

numpy: Para operaciones numéricas eficientes y manejo de valores NaN.

matplotlib.pyplot: Para la creación de gráficos estáticos.

seaborn: Para visualizaciones estadísticas atractivas y avanzadas.

Los pasos clave del análisis incluyen:

Carga de Datos: Importación de los datasets de Google Play Store y Apple App Store.

Limpieza de Datos:

Manejo de valores faltantes (NaN).

Eliminación de duplicados.

Corrección y estandarización de tipos de datos (conversión de strings a numéricos donde sea apropiado, manejo de unidades como 'M', 'K', 'G' para el tamaño, y conversión de rangos de instalación a valores numéricos).

Manejo de valores especiales como 'Varies with device'.

Análisis Exploratorio de Datos (EDA):

Estadísticas descriptivas básicas.

Análisis de la distribución de variables clave (precios, tamaños, ratings).

Identificación de top N aplicaciones por diferentes métricas (descargas, ratings).

Análisis Profundo y Generación de Insights:
Precios: Distribución, impacto en popularidad/rating, comparación entre tiendas.
Tamaño: Correlación con rating/popularidad, distribución por género.
Ratings y Reseñas: Uso de diferentes métricas de rating (user_rating, rating_count_tot, etc.) para comprender la satisfacción del usuario y la popularidad.
Géneros/Categorías: Tendencias específicas de cada mercado.
Actualizaciones y Versiones: Impacto en la percepción del usuario.
Características Adicionales (Apple Store): Análisis de idiomas soportados, dispositivos, y el impacto de licencias VPP.
Visualización de Datos: Creación de gráficos informativos (histogramas, box plots, scatter plots, gráficos de barras) para comunicar los hallazgos.

Al final generamos un archivo nuevo de googleplaystore.csv es mucho mas limpio borramos los datos que contenian datos nulos 
