# Modelo de predicción - Precio Diamantes 💎

![](https://github.com/PaulaElizagarate/Proyecto-Machine-Learning/blob/main/images/Portada.png)


Este es un proyecto de Machine Learning cuyo objetivo es encontrar el mejor modelo predictivo para el precio de los diamantes, utilizando diferentes combinaciones de datos. Se han empleado varias técnicas de aprendizaje automático, como árboles de decisión, Gradient Boosting y Random Forest.

## Estructura del proyecto

El proyecto se ha organizado en tres carpetas principales:

- `data`: contiene los CSVs utilizados y los modelos creados.
- `notebooks`: aquí se desarrollaron los distintos modelos.
- `images`: contiene las imágenes utilizadas para este README.


## Bibliotecas utilizadas

- `Pandas y Numpy`: para el procesamiento de los datos.
- `Matplot y Seaborn`: para la visualización de los datos.
- `Decision Tree`, `Gradient Boost` y `Random Forest`: bibliotecas de Machine Learning utilizadas para crear los modelos predictivos.

## Archivos

- `train.csv`: conjunto de datos utilizado para el entrenamiento y la validación de los modelos.
- `test.csv`: conjunto de datos utilizado para realizar las predicciones.

  ### 1er procesamiento de datos

  - `Kaggle Competition Train`
  - `Kaggle Competition Test`
  - `mejor_modelo.pkl`: archivo pickle que contiene el modelo de predicción realizado con Decision Tree.
  - `mejor_modelo1.pkl`: archivo pickle que contiene el modelo de predicción realizado con Random Forest.
  - `mejor_modelo2.pkl`: archivo pickle que contiene el modelo de predicción realizado con Gradient Boosting.


  ### 2do procesamiento de datos

  En este caso hemos excluido las variables `x`,`y` y `z`, siendo peores modelos que si tuviéramos en cuenta todas. 

  - `modelo1.pkl`: archivo pickle que contiene el modelo de predicción realizado con Decision Tree.
  - `modelo2.pkl`: archivo pickle que contiene el modelo de predicción realizado con Random Forest.
  - `mejor_modelo2.pkl`: archivo pickle que contiene el modelo de predicción realizado con Gradient Boosting


  ### Submissions de la competición de Kaggle

  - `submission`: predicción submiteada.
  - `submission2.csv`: predicción submiteada.
  - `submision_03.csv`: predicción submiteada.
  - `submision_04.csv`: predicción submiteada.
  - `submision_05.csv`: predicción submiteada.
  - `submision_06.csv`: predicción submiteada.

## Análisis exploratorio de los datos.

- Preprocesamiento de los datos, incluyendo limpieza y transformación de variables.
- Creación de varios modelos utilizando diferentes técnicas de Machine Learning.
- Validación cruzada de los modelos para seleccionar el mejor.
- Ajuste de los hiperparámetros del modelo seleccionado.
- Evaluación del modelo final utilizando el conjunto de datos de validación.
- Creación de un archivo pickle con el modelo final.
- Realización de predicciones utilizando el archivo pickle y un conjunto de datos nuevo.

## Conclusiones

Se ha creado un modelo de predicción preciso y robusto para el precio de los diamantes. El modelo seleccionado, Random Forest, es una técnica de Machine Learning adecuada para este problema en particular. Este modelo podría ser utilizado por joyerías o comerciantes de diamantes para predecir los precios de los diamantes con una alta precisión.


## Contáctame

Para más información, sugerencias o dudas, por favor, contactad conmigo:
[Paula Elizagarate](https://www.linkedin.com/in/paulaelizagarate/)

![](https://www.reactiongifs.com/r/dbts.gif)
