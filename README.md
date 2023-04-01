# Modelo de predicción - Precio Diamantes 💎

Este es un proyecto de Machine Learning cuyo objetivo es encontrar el mejor modelo predictivo para el precio de los diamantes, utilizando diferentes combinaciones de datos. Se han empleado varias técnicas de aprendizaje automático, como árboles de decisión, Gradient Boosting y Random Forest.

## Estructura del proyecto

El proyecto se ha organizado en tres carpetas principales:

- `data`: contiene los CSVs utilizados y los modelos creados.
- `notebooks`: aquí se desarrollaron los distintos modelos.
- `images`: contiene las imágenes utilizadas para este README.


## Bibliotecas utilizadas

-`Pandas y Numpy`: para el procesamiento de los datos.
-`Mapplot y Seaborn`: para la visualización de los datos.
-`Decision Tree`, `Gradient Boost` y `Random Forest`: bibliotecas de Machine Learning utilizadas para crear los modelos predictivos.

## Archivos

diamonds.csv: conjunto de datos utilizado para el entrenamiento y la validación de los modelos.
diamonds_predict.csv: conjunto de datos utilizado para realizar las predicciones.
diamonds_model.pkl: archivo pickle que contiene el modelo de predicción final.
Descripción del proceso
Para la creación de los modelos predictivos, se siguió el siguiente proceso:

## Análisis exploratorio de los datos.

-Preprocesamiento de los datos, incluyendo limpieza y transformación de variables.
-Creación de varios modelos utilizando diferentes técnicas de Machine Learning.
-Validación cruzada de los modelos para seleccionar el mejor.
-Ajuste de los hiperparámetros del modelo seleccionado.
-Evaluación del modelo final utilizando el conjunto de datos de validación.
-Creación de un archivo pickle con el modelo final.
-Realización de predicciones utilizando el archivo pickle y un conjunto de datos nuevo.

## Conclusiones

Se ha creado un modelo de predicción preciso y robusto para el precio de los diamantes. El modelo seleccionado, Random Forest, es una técnica de Machine Learning adecuada para este problema en particular. Este modelo podría ser utilizado por joyerías o comerciantes de diamantes para predecir los precios de los diamantes con una alta precisión.





