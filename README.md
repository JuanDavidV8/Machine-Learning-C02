# MACHINE LEARNING AGRO PROJECT
Este proyecto se basa en un análisis de las emisiones de dióxido de carbono (CO2) vinculadas a la industria agroalimentaria, que desempeña un papel crucial al contribuir con el 62% de las emisiones globales de CO2. El objetivo primordial radica en anticipar las emisiones a futuro de CO2 y determinar si influye o no en el cambio climático. Para alcanzar este propósito, se enfoca en dos variables fundamentales: las emisiones totales de CO2, representada por el label 'total_emission', y la temperatura promedio, representada por el label, 'Average Temperature °C'.

La adopción de estas variables persigue generar una comprensión más a fondo y efectiva de la dinámica de emisiones en el ámbito agroalimentario y su relación con los cambios climáticos. Se busca identificar patrones y relaciones entre las emisiones y las variaciones térmicas. A partir de estos hallazgos, se aspira a plantear y descubrir vías potenciales de mitigación, delineando acciones concretas que puedan contribuir a abordar eficazmente esta problemática ambiental.

La metodología involucra análisis estadísticos avanzados y técnicas de modelado predictivo, aprovechando herramientas de Machine Learning para anticipar los futuros escenarios de emisiones de CO2. Este análisis se muestra como un instrumento importante para estimar los efectos del aumento de emisiones en el sistema climático global y orientar la toma de decisiones informadas.

Este proyecto persigue comprender y proyectar las emisiones de CO2 en la industria agroalimentaria, a la vez que busca conceder mayores herramientas a los tomadores de decisiones con información crucial para encarar desafíos ambientales críticos y fomentar prácticas que tengan como objetivo un futuro sostenible.

## Contexto Empresarial
Con el paso de los años, las emisiones de CO2 han experimentado un incremento constante, a la par que la temperatura promedio en cada continente ha seguido una tendencia al alza. Esta dinámica ascendente se ha mantenido a lo largo del tiempo.

Se tienen registros desde el año 1990 hasta el año 2020 en cada una de las variables que comprenden el data set.

Deseamos estimar los efectos futuros de las emisiones para poder tomar decisiones referentes a la prevención y como se pueden disminuir los efectos del CO2 y así encarar de mejor forma los desafios ambientales actuales como el cambio climatico.

## Contexto Analítico: 
Se tiene un data set en archivo tipo CSV llamado "Agrofood_co2_emission.csv" que se encuentra almacenado en la catpera de "Bases de datos" en Drive.

El data set tiene variables de interés como:

Total Population - Female
Total Population - Male
total_emission
Average Temperature °C
Implemetaré las siguientes tareas con los datos:

**1- Transformación y preparación de los datos para las visualizaciones.**

**2- Limpieza del Dataset.**

**3- Creación de las visualizaciones para obtener insights y responder preguntas problema.**

Las preguntas a responder los son las siguientes:

- *¿Cuál ha sido el comportamiento de la temperatura promedio con el paso de los años?*

- *¿Las emisiones de CO2 han aumentado, disminuido o se han mantenido estables en los últimos años?*

- *¿Cuál es el continente que más aporta con emisiones de CO2 a lo largo de los años?*

- *¿Cuál ha sido la variación de la temperatura en cada continente a lo largo de los años?*

- *¿Existe una correlación entre la temperatura promedio y las emisiones de CO2?*

- *¿La temperatura promedio presenta muchos valores atipicos?*

**4- Creación de nuevas variables y reducción de dimensionalidad utilizando la técnica PCA.**

**5- Optimización de parámetros utilizando GridSearchCV.**

**6- Entrenamiento del Dataset con los siguientes algoritmos.**

- Random Forest Regressor
- GradientBoosting
- AdaBoost
- XGB Regressor
