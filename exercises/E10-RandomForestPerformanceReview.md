# E10 - Random Forest Performance Review

Read and comment the paper *Do we Need Hundreds of Classifiers to Solve Real World Classification Problems?*

### Reference:
http://jmlr.org/papers/volume15/delgado14a/delgado14a.pdf


Sin duda este es un trabajo que valoraremos profundamente los apasionados por el Machine Learning, poder tener una comparación tan profunda, tan bien estructurada y tan completa nos da la respuesta a que modelo escoger a la hora de enfrentarnos a un problema de analitica. el primer hallazgo que llama la atención es la amplia lista de clasificadores (179) disponibles para realizar clasificaciones y predicciones, ya de por si este numero es grande, existen otros articulos con similar objetivo en estadístistica y en otros ramos que buscan la comparación de 2 0 3 modelos y que tienen un profundo impacto, ahora imaginamos 179 y somos conscientes de la amplitud de este estudio. Por otro lado tenemos las BD, no se tomaron unas pocas, sino que al estilo del tratamiento de Big Data se incluye una lista de 112 BD, estos numeros mas la busqueda den una estrcutura de comparación equitativa hace que los resultados tengan validez lógica y aplicabilidad a la realidad. para familiarizarnos con los modelos aplicados el paper los agrupa asi:
    Discriminat Analysis (DA): 20 clasificadores
    Bayesian approaches (BA): 6 clasificadores
    Neural Networks (NNET): 21 clasificadores
    Support Vector Machines (SVM): 20 Clasificadores
    Decision Tree (DT): 14 Clasificadores
    Rule-based Methods (RL): 12 Clasificadores
    Boosting (BST): 20 Clasificadores
    Bagging (BAG): 24 Clasificadores
    Stacking (STC): 2 Clasificadores
    Random Forest (RF): 8 Clasificadores
    Other Ensambles (OEN): 11 CLasificadores
    Generalized Linear Models (GLM): 5 Clasificadores
    Nearest Neighbor Methods (NN): 5 Clasificadores
    Partial Least Squares and Principal Component Regresion (PLSR): 6 Clasificadores
    Logistic Multinomial Regression (LMR): 3 Clasifiacdores
    Multivariate Adaptative Regression Splines (MARS): 2 Clasificadores
    Others Methodos (OM): 10 Clasificadores

Este listado tan amplio nos lleva a otro aspecto muy importante que menciona el artículo y es que justamente el investigador siempre tiende a usar solo los modelos que conoce, lo cual en principio nos puede llevar a pesar que se puede estar perdiendo de otro modelo más eficiente, sin embargo como se ve en los resultados, lo más conocidos como RF son los más potentes, el exito de la aplicación de estos modelos radica mucho en el conjunto de entrada, en las caracteristicas de las variables involucradas y en la información y correlación que tenga la BD con la variable objetivo.  Ahora bien como en toda medición la unica forma de lograr una comparación objetiva es a tarvés de un indice que nos permita facilmente comparar los resultados, es por ellos que el paper, describe 3 indices; 
Average Accuracy and Friedman Ranking
Probability of Achieving the Best Accuracy (PAMA)
El resultado general y que es consistente de acuerdo a los indices establecidos es que los modelos de RF son los mas eficientes en general, seguidos por SVM (sorpresa para mi), en tercer lugar NNET (a este ultimo modelo le tenia una mayor expectativa) y finalmente tenemos los modelos clasicos estadistico los cuales estan en la parte inferior de la lista.

Una cosa que llama profundamente la atención es que para realizar esta comparaci{on se usaron tambien diversos programas computacionales, dentro de los cuales extrañamente no apreciamos a Python, el lenguaje que a mi modo de ver a revolucionada el analisis de informaci{on.

En conclusión este paper presenta un investigación muy amplia para poder tener una comparación equitativa de la gran variedad disponibles de modelos de clasificación. cuyo resultado nos lleva a asegurar que el mejor resultado lo tiene Parallel Random Forest. 
