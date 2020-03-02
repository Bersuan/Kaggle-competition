# Kaggle-competition

![FotoPortada](https://raw.githubusercontent.com/bersuan/Kaggle-competition/master/input/kaggle.jpg)

En este proyecto nos enfrentamos a una competicion de entrenamiento de modelos, para llevarlo a cabo nos han dado un dataset de diamantes, del cual teniamos que predecir su precio seleccionando las features adecuadas.

Para intentar optimizar el programa que realizado una limpieza del dataset de la siguiente manera:
1. Creo una columna volumnen con un .apply() multiplicando el peso por la densidad del diamante.
2. elimino las X,Y y Z.
3. Hago un get_dummies para convertir las variables categoticas

En mi caso el modelo mas óptimo a sido el de RandomForestRegressor.
