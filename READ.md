
# Análisis de Spotify - All Time Top 2000s Mega Dataset

**Autor:** Katia Keller  
**Curso:** Herramientas básicas para el Análisis de Datos

## Descripción General y Objetivo
 El dataset **Spotify - All Time Top 2000s Mega Dataset** reúne un catálogo de las 2.000 canciones más destacadas de la plataforma. A través de métricas acústicas como ritmo (BPM), bailabilidad (*danceability*), energía (*energy*) y popularidad (*popularity*), este proyecto explora los factores que definen un éxito musical.

**Preguntas:**
* **Evolución Temporal:** ¿Cómo variaron las características sonoras según el año de lanzamiento (`year`)?
* **Factores de Popularidad:** ¿Existe correlación entre las métricas acústicas y la popularidad (`popularity`)?
* **Distribución:** ¿Qué géneros (`top_genre`) y artistas concentran más éxitos?

## Fuente y Herramientas
* **Dataset:** Spotify Top 2000s (https://www.kaggle.com/datasets/iamsumat/spotify-top-2000s-mega-dataset).
* **Herramientas:** Python (Pandas, NumPy, Matplotlib, Seaborn) para limpieza y EDA; Power BI para modelado y dashboard interactivo; GitHub para documentación.

## Estructura y Enlaces

### Estructura
* `/data/raw/`: Archivo `.csv`.
* `/notebooks/`: Google Colaboratory.
* `/dashboard/`: Archivo `.pbix` y captura `.png`.
* `README.md`: Documentación principal.

### Enlaces
**Dataset:** https://www.kaggle.com/datasets/iamsumat/spotify-top-2000s-mega-dataset
**GitHub:** https://github.com/katiakeller/herramientasbasicas-keller-katia

## Pasos Realizados
1. **EDA en Colab:** Limpieza de nulos, formateo de variables y gráficos.
2. **Dashboard Interactivo:**
   * **3 KPIs (Tarjetas):** Total canciones, popularidad y energía promedio.
   * **2 Visuales Dinámicas:** Top géneros y tendencias por año.
   * **1 Tabla de Detalle:** Vista tabular.
   * **Panel de Control:** Segmentador de datos.

## Conclusiones Principales

* **Popularidad:** La mayoría de las cacniones del catálogo se concentran en niveles de popularidad medios-altos. 
* **Evolución:** Tendencia clara de transformación en la industria musical.
* **Concentración:** Un grupo reducido de géneros domina el catálogo histórico. 
* **Tendencias:** Las producciones recientes muestran mayor nivel de energía y bailabilidad.

## Citas
* Dataset Source: *Spotify Top 2000s Dataset*, Kaggle. (https://www.kaggle.com/datasets/iamsumat/spotify-top-2000s-mega-dataset)
* Documentación: *Microsoft Power BI *.