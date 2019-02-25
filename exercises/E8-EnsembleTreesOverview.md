# E8 - Ensemble Trees Overview

Write at least 300 words explaining why ensemble is a succesful strategy in machine learning.

En general la aplicación de una técnica o modelo busca con solo esta técnica o modelo obtener el mejor resultado, esto se busca tratando de especificar las variables más relevantes o calculando los parámetros que mejor resuman la información y que de esta manera permitan los mejores pronósticos o descripciones de un evento dado, como por ejemplo en arboles de decisión, cuyas variantes pueden generar diversos resultados. Esta búsqueda incesante aplica para todos los modelos, sin embargo, los modelos siempre resultan con una mezcla de fortalezas y debilidades, lo que limita o acota sus resultados. y si existiera un método de combinar los modelos y que el resultado fuera mejor que cualquier resultado individual??? esto justamente es lo que logra el ensamble de modelos, en principio uno puede pensar que al combinar modelos el resultado agregado se pueda deteriorar por la inclusión de modelos no óptimos o que en el mejor de los casos fuera igual, sin embargo gracias al teorema de Condorcet se demuestra que la combinación de los modelos, cuando sus probabilidades de resultados favorables de manera individual son superiores al 50% resultan de manera combinada con una probabilidad superior de resultados favorables, esto realmente resulta grandioso ya que da la oportunidad de probar e incluir múltiples modelos y lograr un mejor resultado. la combinación de los modelos se puede realizar de diversas maneras, 2 por ejemplo son; regresión y clasificación. En el primero se hace un promedio de las predicciones individuales de los modelos, mientras en el segundo se toma como combinación el resultado más común (más votado) o también se puede tomar el promedio de las predicciones de probabilidad.

Se han desarrollado múltiples sistemas para combinar los modelos de reconocimiento de patrones; dentro de los principales encontramos;
Modelos de promedio bayesiano: 
Votación Simple: es el método más ampliamente usado, debido a su facilidad de implementación.
Votación Ponderada: al sistema de votación anterior se le adiciona una penalización o bonificación de acuerdo con la especialización de los modelos de clasificación considerados en el ensamble. 
Bagging
Boosting: Combinación de múltiples clasificadores para producir una forma de comité 
Modelos basados en árboles
Modelos de mezclas condicionadas (modelos de Regresión, modelos Logísticos y mezclas de expertos)
Redes neuronales adaptativas
Conditional Random fields

Además de las bondades obvias de tener una mejor predicción, las razones de uso de los modelos de ensamble son; estadísticas, el poder procesar grandes volúmenes de información, la necesidad de tener una según opinión, poder analizar grupos más pequeños de datos y aun así lograr un resultado más preciso (accuracy)






