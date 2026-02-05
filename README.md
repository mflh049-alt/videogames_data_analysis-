# Análisis de Drivers de Ventas en la Industria de Videojuegos
Identificación de patrones de éxito comercial 

Este proyecto analiza datos históricos de ventas de videojuegos por región, plataforma y género con el objetivo de identificar patrones asociados al éxito comercial. El análisis se plantea en un escenario hipotético en el que la tienda online Ice busca planificar campañas publicitarias futuras a partir de información disponible hasta 2016.

Al explorar las dinámicas del mercado en regiones como Norteamérica, Europa y Japón, el proyecto busca aportar insights que apoyen la toma de decisiones en estrategias de marketing y la identificación de títulos con mayor potencial comercial. 

## Preguntas Clave
- ¿Qué platafromas y géneros concentran mayores ventas? ¿Cómo varían las ventas por región?
- ¿Existe relación entre las reseñas de usuarios y críticos con el desempeño de las ventas?
- ¿Las clasificaciones de edad (ESRB) influyen en el éxito comercial?
- ¿Qué tendencias se observan en el mercado en los años más recientes conforme a los datos analizados?

## Herramientas utilizadas 

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-357ebd?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Orange?style=for-the-badge&logo=jupyter&logoColor=white)

![EDA](https://img.shields.io/badge/Análisis_Exploratorio_de_Datos-295F98?style=for-the-badge)
![Visualización](https://img.shields.io/badge/Visualización_de_Datos-295F98?style=for-the-badge)
![Hipótesis](https://img.shields.io/badge/Pruebas_de_Hipótesis-295F98?style=for-the-badge)

## Proceso de análisis 
1. Limpieza y preparación de datos
2. Análisis exploratorio de variables clave: identificación de genéros y plataformas líderes en ventas, evlacución de la correlación entre las reseñas y el desempeño de las ventas
3. Análisis por región: Identificación de géneros y platafromas líderes en Norteamérica, Europa y Japón.
4. Análisis estadístico para contrastar hipótesis

## Principales Hallazgos 
### Análisis exploratorio por región, géneros y plataformas 
- Se identificaron diferencias significativas en ventas entre plataformas y géneros.
- Las reseñas de críticos muestran una relación más consistente con las ventas que las reseñas de usuarios.
- Algunas clasificaciones ESRB presentan patrones de ventas diferenciados según el tipo de juego.

### Pruebas de hipótesis
- Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son iguales.
- Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.

*Los resultados completos se detallan en el notebook del proyecto* 

## Estrategia recomendada

## Diccionario de datos 
| Variable | Descripción |
|--------|-------------|
| name | Nombre del videojuego |
| platform | Plataforma de lanzamiento |
| year_of_release | Año de lanzamiento |
| genre | Género del videojuego |
| rating | Clasificación ESRB |
| na_sales | Ventas en Norteamérica (millones) |
| eu_sales | Ventas en Europa (millones) |
| jp_sales | Ventas en Japón (millones) |
| other_sales | Ventas en otras regiones |
| global_sales | Ventas globales |




   
