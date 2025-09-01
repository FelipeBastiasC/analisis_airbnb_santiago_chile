# Análisis del Mercado de Airbnb en Santiago de Chile

![Banner del Proyecto](images/Banner.png)

## 📜 Resumen del Proyecto

Este proyecto presenta un Análisis Exploratorio de Datos (EDA) del mercado de alquileres a corto plazo de Airbnb en Santiago de Chile. El objetivo es descubrir patrones clave en la distribución de precios, la concentración geográfica de las propiedades y las características que definen la oferta. Este análisis sirve como base para entender la dinámica del mercado, tanto para viajeros como para anfitriones potenciales.

---

## 🎯 Objetivos del Análisis

Las preguntas clave que guiaron este análisis fueron:

1.  **Distribución Geográfica:** ¿En qué comunas de Santiago se concentra la mayor cantidad de propiedades de Airbnb?
2.  **Análisis de Precios:** ¿Cuál es la distribución de precios por noche y qué comunas presentan los precios promedio más altos y bajos?
3.  **Características de las Propiedades:** ¿Qué tipo de propiedades (apartamento, habitación privada, etc.) son las más comunes y cómo influye esto en el precio?
4.  **Popularidad:** ¿Existe alguna relación entre el precio y la popularidad de una propiedad (medida por el número de reseñas)?

---

## 💡 Hallazgos Principales

1.  **Concentración en el Sector Oriente:** La oferta de Airbnb está fuertemente concentrada en las comunas de **Providencia, Santiago y Las Condes**, que juntas representan más del 70% del total de las propiedades.
2.  **Precios Exclusivos en el Sector Nororiente:** Aunque no tienen la mayor cantidad de propiedades, comunas como **Vitacura y Lo Barnechea** lideran consistentemente en el precio promedio por noche, superando los $100,000 CLP.
3.  **Predominio de "Apartamentos Completos":** La categoría "Entire home/apt" es la más común y también presenta la mayor variabilidad de precios, conteniendo tanto opciones económicas como las más lujosas del mercado.
4.  **La Popularidad no Siempre es Cara:** No se observa una correlación lineal fuerte entre el precio y el número de reseñas. Esto sugiere que las propiedades más populares no son necesariamente las más caras, sino aquellas que probablemente ofrecen una mejor relación calidad-precio.

---

## 📊 Dashboard en Power BI

Para consolidar y visualizar los hallazgos de este análisis, desarrollé un dashboard interactivo en Power BI. A continuación se muestra la vista principal de este dashboard.

### Vista General del Dashboard

![Vista General del Dashboard](https://github.com/FelipeBastiasC/analisis_airbnb_santiago_chile/blob/f0568561423a65bd66dd850f067167f8b69f3ced/images/Dashboard%20Airbnb%20Santiago%202%20.png)

---

## 🛠️ Herramientas Utilizadas

*   **Lenguaje:** Python
*   **Librerías de Análisis:** Pandas, NumPy
*   **Librerías de Visualización:** Matplotlib, Seaborn
*   **Herramienta de BI:** Microsoft Power BI
*   **Entorno:** Jupyter Notebook, VS Code

---

## 🚀 Cómo Explorar este Repositorio

*   **/analisis_airbnb_santiago.ipynb**: Contiene el código completo del análisis, desde la limpieza de datos hasta la generación de todas las visualizaciones y conclusiones detalladas.
*   **/data/AirBnb_chile.csv**: El conjunto de datos descargado desde Kaggle utilizado para el análisis en el notebook.
*   **/data/df_limpio.csv**: El conjunto de datos limpio utilizado para el análisis en el notebook y para la creación del dashboard en Power BI.
*   **/data/dashboard_airbnb.pbix**: El dashboard creado en Power BI para la visualización de la distribución de Airbnb en Santiago de Chile.
*   **/images/**: Carpeta con las imágenes y gráficos utilizados en esta documentación.
