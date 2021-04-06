# NLP-prediccion-de-clasificacion-Reviews-Amazon

Personal Projects with learning objectives


El objetivo era predecir la cantidad de estrellas que tenia una review, o sea clasificarla de que tan buena o mala era segun el procesamiento del texto de la review con NLP y el uso de estos datos en modelos de machine learning de regresión. 

Utilice dos modelos, ambos dentro de un pipeline cuyos hiperparametros fueron optimizados con Cross Validation y ambos obtuvieron errores muy parecidos:
  * En primer lugar un modelo de Regresión lineal con regularización Ridge 
  * En segundo lugar utilice XGBoost 
El error obtenido por ambos modelos fue de un RMSE de 1 estrella.


También en el análisis exploratorio hice un "aplicativo" donde se ingresa una palabra y te muestra todos los datos sobre la misma, o sea cuantas veces aparece, en que categorias aparece mas, en que estrellas y un cruce entre ambas.


Dataset: https://registry.opendata.aws/amazon-reviews-ml/
Licencia Dataset: https://docs.opendata.aws/amazon-reviews-ml/license.txt


