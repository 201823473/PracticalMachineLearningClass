# E5 - Decision Trees Overview

Write at least 300 words explaining the types of decision trees algorithms and applications.

La facilidad de entendimiento tanto de los resultados de los árboles de decisión, así como de su construcción y conceptualización hace de esta técnica una herramienta muy usada para desarrollar y poder explicar fácilmente el concepto de clasificación de elementos.  El árbol está compuesto por nodos que representan atributos, cada conexión (rama) una regla de decisión y cada hoja una categoría de salida.  Para construir cada árbol entonces se desarrollan algoritmos para determinar qué y cuantas ramas debe tener el árbol. Los principales algoritmos disponibles para tal fin son; 
•	CART (Clasification and Regresion Tree) que usa el índice de Gini como métrica de clasificación 
•	ID3 (Iterative Dichotomiser 3) que usa una función entrópica e información de ganancia como métricas 
•	C4.5 (Sucecor de ID3)
•	CHAID (Detector automático de Chi-cuadrado de interacción) Realiza divisiones de múltiples niveles al calcular loa arboles de decisión 
•	QUEST (Chi-square for categorical variable) 

El algoritmo CART utiliza para su construcción datos históricos, cuya variable de respuesta pueden ser numéricas o categóricas, se destaca su robustez ya que no se deja afectar por datos atípicos (Outliers), tiene 3 pasos, que son; primero construcción del árbol saturado, dos escogencias del tamaño correcto del árbol y tres, clasificación de nuevos datos usando el árbol construido. La construcción del árbol se realiza por particionamiento recursivo a través de la medida de impurezas y la bondad de una división, el segundo paso es entonces la poda del árbol, es decir la selección del subárbol del árbol saturado que tenga la mejor calidad en cuanto a predicción y robustes.    
El algoritmo ID3 es utilizado con el racional de la inteligencia artificial, es decir usa información real del resultado esperado de la clasificacación para construir el árbol y de esta manera poder llegar a una regla general que permita la clasificación de nuevos eventos no contemplados inicialmente en el árbol
C4.5 es un algoritmo que construye arboles con el mismo principio de inteligencia artificial, al igual que el ID.3, usando el concepto de entropía de la información, el criterio es normalizado para ganancia de la información, el atributo con mayor ganancia de información es el que se usa de criterio o parámetro de decisión.
Algoritmo CHAID para buscar asociaciones entre variables y lograr segmentación de mercados, este método busca en cada paso elegir la variable independiente (predictora) que presenta la interacción más fuerte con la variable dependiente. El objetivo principal es el obtener tipologías y perfiles de los consumidores o usuarios.
Finalmente tenemos el algoritmo QUEST que funciona muy similar al algoritmo CHAID, con la diferencia de que la partición de los nodos se hace como una combinación lineal. 
