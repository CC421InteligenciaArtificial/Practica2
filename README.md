# Grupo 6
### Diego Bergna Aguilar
### Kevin Paima Mijahuanca
### Stefano Olivieri Romero
### Italo Silva Guanilo
El trabajo actual consta de un entrenamiento de una data muy amplia la cual fue sometida a diferentes métodos de entrenamiento para asi poder encontrar el que se adapte mejor al 
caso, para la lectura de documentos se debe usar el siguiente orden:
* Carga de datos
* Procesamiento
* Entrenamiento
* ParteFinal

  Para la experimentación se uso una muestra de 1.5 millones de datos generando asi una guía para generar una conclusión de nuestro experimento, del cual podemos ver los siguientes datos:
+ Random Forest = 0.787740
+ Regresion Lineal = 0.00228
+ Gradient Boost Regression = 0.795946
+ Knn Regression [Diego] = 0.782802 (KNN probado en el ordenador de Diego Bergna)
+ Knn Regression [Kev] = 0.7779 (KNN probado en el ordenador de Kevin Paima)
+ Baggin Regressor = 0.74

  Como podemos ver en este lista de resultados la acertiviudad, él modelo con mayor puntuación el el GradientBoostRegression con un valor cercano al 0.8, pero debemos considerar el tiempo como un factor importante:
1. GradientBoostRegression
2. RandomForest
3. KNN
4. Baggin 
5. LinearRegression

  
  Es importante agregar que en el caso del LinearRegression el tiempo fue mucho mayor que en los otros casos. Gracias a estos datos podemos notar que el modelo GradientBoosterRegression es el mas indicado.

