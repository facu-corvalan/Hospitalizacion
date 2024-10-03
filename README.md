
<h2 align="center"><strong style="font-size: 1.2em;">🚑 &nbsp;Modelo Predictivo de Hospitalización</strong></h2>

![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas)
![Numpy](https://img.shields.io/badge/-Numpy-333333?style=flat&logo=numpy)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-333333?style=flat&logo=matplotlib)
![Seaborn](https://img.shields.io/badge/-Seaborn-333333?style=flat&logo=seaborn)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-333333?style=flat&logo=scikit-learn)

## **Introducción**

¡Bienvenidos a nuestro proyecto integrador! Este proyecto pondrá en práctica las habilidades adquiridas en Machine Learning y su aplicación en un contexto médico real. A lo largo de este trabajo, realizaremos análisis exploratorio de datos, preparación de datos y experimentación con diferentes modelos de clasificación. El objetivo final es medir el rendimiento de los modelos utilizando métricas apropiadas y seleccionar el mejor modelo predictivo.

Este proyecto es una excelente oportunidad para incluir en tu portafolio, ya que aborda problemas reales y muestra habilidades avanzadas de ciencia de datos.

## **Planteamiento de la problemática**

En este proyecto, hemos sido contratados por un hospital que desea conocer las características más relevantes de los pacientes que, tras una biopsia prostática, son hospitalizados debido a complicaciones infecciosas. Nuestro objetivo es construir un modelo predictivo que clasifique a los pacientes entre aquellos que requerirán hospitalización y los que no, utilizando datos históricos proporcionados por el hospital.

### **Datos disponibles**

El hospital nos ha proporcionado una base de datos que incluye variables como:
- `Antecedentes del paciente`
- `Morbilidad asociada`
- `Información sobre la biopsia`
- `Complicaciones infecciosas`


## **Fases del proyecto**

### 1. **Análisis exploratorio de datos (EDA)**
Durante el EDA, identificaremos patrones y relaciones entre las variables disponibles y la variable objetivo (hospitalización). Se utilizarán herramientas como gráficos y métricas estadísticas para visualizar y entender los datos. Este proceso también incluye la detección de valores faltantes y problemas de calidad de datos, los cuales serán abordados en la siguiente fase.

### 2. **Preparación de los datos**
El siguiente paso es limpiar y transformar los datos, asegurándonos de que estén listos para ser utilizados en los modelos de Machine Learning. Esto incluye la imputación de valores faltantes, codificación de variables categóricas, y la normalización de los datos según sea necesario.

### 3. **Modelamiento y evaluación**
Finalmente, implementaremos varios modelos de clasificación para predecir la hospitalización, incluyendo:
- Árboles de Decisión
- K-Nearest Neighbors (KNN)
- Máquinas de Soporte Vectorial (SVM)

Para mejorar el rendimiento, se aplicarán técnicas de reducción de dimensionalidad como PCA (Análisis de Componentes Principales), y se realizará una búsqueda exhaustiva de hiperparámetros usando GridSearch para optimizar cada modelo.



## **Conclusiones**

El resultado esperado de este proyecto es un modelo que pueda predecir con precisión qué pacientes serán hospitalizados tras una biopsia prostática, basado en sus antecedentes y complicaciones. La métrica de evaluación principal será el **F1 Score**, que nos permitirá balancear la precisión y exhaustividad del modelo, especialmente relevante dado el desbalance en la variable objetivo.

---