

# <h1 align=center> **PROYECTO INDIVIDUAL Nº2** </h1>

# <h1 align=center>**`Machine Learning` 🤖 **</h1>

## **Introducción :paperclip:**

Les presento mi segundo proyecto individual de la etapa de Labs :microscope:!
En esta ocasión, les mostraré como hacer un trabajo situándome en el rol de una experta en ***Machine Learning***. Pasaremos por un preprocesamiento de datos, que incluye el análisis exploratorio de los mismos (EDA), para poder contar con datos de calidad que nos permitan, a su vez, entrenar un modelo capaz de generar predicciones con un alto porcentaje de precisión y exhaustividad.  

## **Objetivo :paperclip:**

Contamos con 2 archivos .csv que contienen información sobre la estadía de pacientes en instituciones hospitalarias. Se pretende generar un modelo de clasificación que permita predecir si un paciente tendrá una estadía larga (más de 8 días) o corta (8 días o menos) en función de las variables disponibles, a su vez, la performance de dicho modelo se medirá a partir de 2 metricas ***Recall*** y ***Accuracy***

  
## **Pasos del proyecto :paperclip:**

1:small_blue_diamond: Ingesta de datos y Análisis exploratorio de los mismos ***(EDA)***

2:small_blue_diamond: Analizar que tipo de problemática deseaba responder mi modelo: en este caso vemos que es de ***Clasificación***

3:small_blue_diamond: Elección del modelo: luego de investigar y leer mucha documentación, decidí elegir ***Random Forest*** (bosques aleatorios), ya que contaba con muchas ventajas que aplicaban para este caso (son muy útiles en la exploración de datos, permiten identificar de forma rápida y eficiente las variables más importantes y en muchos casos consigue mejores resultados que un arbol de decisión).

4:small_blue_diamond: Terminamos de adaptar los dataframes para poder utilizar el modelo: transformar los tipos de datos, generar una nueva columna y eliminar aquellas que no tienen correlación con el problema (decidí eliminarlas en base a mi raciocinio, como primera instancia, luego verifique que efectivamente no poseían correlación alguna).

5:small_blue_diamond: Entrenamiento del modelo

6:small_blue_diamond: Verificación de la performance del modelo en base a las métricas Recall y Accuracy

7:small_blue_diamond: Decidí volver a entrenar mi modelo, pero esta vez utilizando Grid Search para analizar los mejores hiperparámetros.

8:small_blue_diamond: Verificación de la performance del modelo luego de utilizar Grid Search, concluyendo que el modelo mejoró, ya que los valores de ambas métricas aumentaron.

9:small_blue_diamond: Finalmente utilizar el modelo para obtener las predicciones buscadas.

10:small_blue_diamond: Guardar las predicciones en un archivo .csv para que puede ser evaluado.


## **Herramientas y lenguajes utilizados :paperclip:**

:small_blue_diamond: Python :snake:
:small_orange_diamond: Pandas :panda_face:
:small_orange_diamond: Sklearn :bar_chart:


## **Gracias por leer! :grin:**


![ia](https://user-images.githubusercontent.com/82453305/207988802-7c8a9e4d-938b-4cc9-aeb2-a960f4695649.jpg)
