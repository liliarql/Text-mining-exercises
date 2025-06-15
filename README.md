# Text-mining-exercises

## EJERCICIO 1

Se trabaja con un conjunto de datos procedente de medios sociales online.

Uno de los mayores problemas del internet hoy en día es la presencia de actitudes negativas hacia algunos colectivos en relación a su etnia, género, religión o ideología política. En este ejercicio trabajaremos con un conjunto de datos reales, etiquetados manualmente, procedentes de la plataforma [Kaggle](https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification/data). Originalmente, a cada documento del dataset se le asignó una de las siguientes categorías:
- *religion*
- *age*
- *ethnicity*
- *gender*
- *other_cyberbullying*
- *not_cyberbullying*


El objetivo inicial del dataset era su uso para entrenar un modelo capaz de detectar el contenido de tipo odio presente en internet según el colectivo al que se atacaba. En este caso, para simplificar el ejercicio, se ha generado una función `load_prepare_data()` que cambia las categorías del dataset obteníendose al final 2 categorías con valor 1 o 0, indicando si el tweet tiene contenido de odio

Para el ejercicio se debe entrenar diferentes modelos de clasificación que permitan clasificar correctamente los tweets. Para ello será necesario crear y utilizar funciones de preprocesado de datos, aplicar estrategias de vectorización de textos como TF-IDF o embeddings, y entrenar/evaluar modelos de clasificación.

## EJERCICIO 2

En este ejercicio se entrena un modelo de clasificación utilizando la librería Transformers. Dado que el análisis exploratorio ha sido realizado en el ejercicio anterior, en este caso se centra en entrenar el modelo utilizando la librería Transformers, seleccionando un modelo pre-entrenado adecuado, entrenando el modelo y llevando a cabo la evaluación.

*Nota:* Estos ejercicios requieren el uso de las GPUs de Google Colab. Este Colab debería estar preconfigurado para ejecutarse en GPU.
