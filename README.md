# Bienvenido al repositorio!  :wave:

Este repositorio almacena proyectos en los que realizo predicciones utilizando modelos de Machine Learning.

[![predicciones-rotacion.png](https://i.postimg.cc/zGs2K1Pw/predicciones-rotacion.png)](https://postimg.cc/87bbgxGs)
## :sparkle: **Proyecto 1**

### Predicción de la rotación de clientes de un banco utilizando datos historícos.
---

Este proyecto tiene como objetivo desarrollar un modelo que permita predecir si un cliente abandonará pronto el banco. Para lograrlo,se utilizan datos históricos sobre el comportamiento pasado de los clientes y la terminación de contratos con la institución financiera.

### Pasos del Proyecto

El proyecto se divide en las siguientes etapas:

1. Análisis de datos: Se realiza un análisis exhaustivo de los datos disponibles para comprender su estructura y características.

2. Preprocesamiento de los datos: Se llevan a cabo tareas de limpieza  y transformación de los datos, con el fin de prepararlos adecuadamente para el entrenamiento de los modelos de clasificación.

3. Tratamiento del desbalance de clases: Dado que es probable que el conjunto de datos esté desbalanceado en términos de clientes que abandonan y los que no, se implementarán técnicas para abordar este problema y asegurar un entrenamiento equilibrado.

4. Prueba de modelos de clasificación: Se explorarán y evaluarán diferentes algoritmos de clasificación, como Regresión Logística, Árboles de Decisión y Bosques Aleatorios. Se ajustarán los hiperparámetros y se comparará su rendimiento.

5. Evaluación del rendimiento de los modelos: Se utilizarán métricas de evaluación, como F1-Score y AUC-ROC, para medir el desempeño de los modelos y seleccionar el más adecuado para la predicción de abandono de clientes bancarios.



**Librerías utilizadas**

El proyecto hace uso de las siguientes librerías de Python:

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Sklearn



[![cancelacion-clientes.png](https://i.postimg.cc/LsZtkYZh/cancelacion-clientes.png)](https://postimg.cc/t1pnpgkH)
## :sparkle: **Proyecto 2**


### Predicciones en tasa de cancelación de clientes de telecomunicaciones Interconnect.

------------

Este proyecto tiene como objetivo desarrollar un modelo que permita predecir su tasa de cancelación de clientes. Si se descubre que un usuario o usuaria planea irse, se le ofrecerán códigos promocionales y opciones de planes especiales. Para logarlo  se obtuvieron datos personales de sus clientes, incluyendo información sobre sus planes y contratos.

#### Pasos del Proyecto

El proyecto se divide en las siguientes etapas:

1. Análisis de datos: Se realiza un análisis exhaustivo de los datos disponibles, debido a que la infromacion se encuentra en diferentes dataset, se analizaron  por separado para comprender su estructura y características, asi como la busqueda de las caracteristicas con mayor correlacion con la caracteristica objetivo, para obtener un dataframe final mediante la union 

2. Preprocesamiento de los datos: Se llevan a cabo tareas de limpieza  y transformación de los datos, con el fin de prepararlos adecuadamente para el entrenamiento de los modelos de clasificación.


3. Prueba de modelos de clasificación: Ya que solo se cuenta con un dataset, este sera segmentado en dataset de entrenamiento y prueba en porporción 3:1, se explorarán y evaluarán diferentes algoritmos de clasificación, como Regresión Logística, KNeigborsclassifier y LightGBM, Random Forest, gradient booster classifier, gausiona nb. Se ajustarán los hiperparámetros y se comparará su rendimiento.

4. Evaluación del rendimiento de los modelos: Se utilizarán métricas de evaluación, como F1-Score , APS, Accuracy y AUC-ROC, para medir el desempeño de los modelos y seleccionar el más adecuado para la predicción de cancelación de clientes. 


**Librerías utilizadas**

El proyecto hace uso de las siguientes librerías de Python:

- Pandas
- Numpy
- Matplotlib
- Scipy
- Sklearn
- lightgbm