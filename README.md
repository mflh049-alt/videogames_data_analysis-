# Análisis de Drivers de Ventas en la Industria de Videojuegos
Identificación de patrones de éxito comercial 

Este proyecto **analiza datos históricos de ventas de videojuegos por región, plataforma y género con el objetivo de identificar patrones asociados al éxito comercial**. El análisis se plantea en un escenario hipotético en el que la tienda online Ice busca planificar campañas publicitarias futuras a partir de información disponible hasta 2016.

Al explorar las dinámicas del mercado en regiones como Norteamérica, Europa y Japón, el proyecto busca **aportar insights que apoyen la toma de decisiones en estrategias de marketing y la identificación de títulos con mayor potencial comercial**. 

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
1. **Limpieza y preparación de datos**
2. **Análisis exploratorio** de variables clave: identificación de genéros y plataformas líderes en ventas, evlacución de la correlación entre las reseñas y el desempeño de las ventas
3. **Análisis por región**: Identificación de géneros y platafromas líderes en Norteamérica, Europa y Japón.
4. **Análisis estadístico** para contrastar hipótesis: comparar calificaciones promedio de usuarios por plataformas y género. 

## Principales Hallazgos 
### Análisis exploratorio por región, géneros y plataformas 
-En los mercados occidentales (Norteamérica y Europa), las plataformas líderes son Xbox One (XONE) y PlayStation 4 (PS4), mientras que en Japón predomina Nintendo 3DS.
A nivel global, los géneros más rentables son Deportes y Acción. Sin embargo, en Japón el género con mayores ventas corresponde a los juegos de rol (RPG)
- Las reseñas de los críticos presentan una correlación positiva débil con las ventas globales, lo que indica que puntajes más altos suelen asociarse con mayores ingresos, aunque con un impacto limitado. En contraste, la relación entre el puntaje de los usuarios y las ventas es prácticamente nula, sugiriendo una influencia mínima en el desempeño comercial.
- Según la clasificación ESRB, los videojuegos con clasificación E (Everyone) concentran el mayor volumen de ventas. No obstante, los títulos clasificados como AO (Adults Only), aunque menos frecuentes, presentan un mayor promedio de ventas por videojuego, lo que los convierte en un nicho rentable en Occidente. En Japón, este comportamiento se observa principalmente en la clasificación K-A.

### Pruebas de hipótesis
- Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son iguales.
- Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.

*Los resultados completos se detallan en el notebook del proyecto* 

## Estrategia recomendada
Se recomienda priorizar las características del prodicto de acuerdo a la región.
-**Adaptar las estrategias por región**, considerando diferencias en plataformas, géneros y clasificaciones por edad.
- En **Norteamérica y Europa**, priorizar campañas para **Xbox One (XONE) y PlayStation 4 (PS4)**; en **Japón**, enfocar los esfuerzos en **Nintendo 3DS**.
- Impulsar juegos de **Deportes y Acción** en mercados occidentales, mientras que en Japón se recomienda priorizar **RPG (Role Play Game)**.
- Orientar campañas de alto alcance a títulos con **clasificación ESRB E**, complementadas con estrategias de nicho para títulos **AO en Occidente y K-A en Japón**.

## Diccionario de datos 
Las siguientes variables conforman el dataset utilizado en el análisis:

- `Name` — Nombre del videojuego.
- `Platform` — Plataforma de lanzamiento (por ejemplo; *Wii, NES, GB*).
- `Year_of_Release` — Año de lanzamiento.
- `Genre` — Género del videojuego (por ejemplo, *Sports, Platform, Racing*).
- `NA_sales` — Ventas registradas en América del Norte, expresadas en millones de unidades.
- `EU_sales` — Ventas registradas  en Europa, expresadas en millones de unidades.
- `JP_sales` — Ventas regitradas en Japón, expresadas en millones de unidades.
- `Other_sales` — Ventas registradas otras regiones, expresadas en millones de unidades.
- `Critic_Score` — Calificación promedio asignada por críticos especializados, medida en una escala de 0 a 100 puntos.
- `User_Score` — Calificación promedio otorgada por usuarios, usualmente expresada en una escala de 0 a 10; en algunos casos puede contener valores no numéricos (por ejemplo, tbd).




   
