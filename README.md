# PANDAS-PROJECT

Este proyecto trata sobre la limpieza y posterior análisis de unos datos obtenidos de *<https://www.kaggle.com/teajay/global-shark-attacks>*, que tratan sobre ataques de tiburones producidos a personas.


Para hacer dicho análisis se proponen dos hipótesis, y con los datos obtenidos, se comprobará si dichas hipótesis son verdaderas o falsas.


 ![image](https://user-images.githubusercontent.com/66179117/91718197-38917c80-eb93-11ea-9be4-ee785737d19d.png)



Este dataset se divide en un total de 24 columnas y 25723 filas

-------

## **Hipótesis y comprobación**

### **Limpieza de datos comunes**
Para empezar, en ambas hipótesis, se han importado los datos y la librería pandas.


<img width="734" alt="importar datos" src="https://user-images.githubusercontent.com/66179117/91725859-962bc600-eb9f-11ea-9334-5fa60bde528e.png">

Seguidamente, se ha realizado una limpieza de datos con todas las filas o columnas NaN, además de los datos duplicados, aplicando al DataFrame *.drop* o *.drop_duplicates()*

### **Hipótesis 1**

La **hipótesis 1** se define como: *"Los ataques fatales de los tiburones blancos suelen ser provocados por el ser humano"*

¿CÓMO SE HA COMPROBADO?

- Se han saleccionado las columnas que podrian ser útiles para dicho estudio, en este caso, conocer si son ataques fatales o no, la especie de tiburón, y si el ataque ha sido provocado o no. 
- Además, la columna sobre la especie se ha filtrado para conocer solamente los datos sobre el tiburón blanco, que son los datos que se necesitarán. Y si dichos ataques han sido efectivamente fatales
- Sobre esos datos ya filtrados, segun el interes de la hipótesis, se han agrupado los ataques "provocados" y "no provocados".
- Se crea una gráfica para una mejor visualización.

   ![Unknown-1](https://user-images.githubusercontent.com/66179117/91731912-c8412600-eba7-11ea-8768-b50882ce6cbe.png)







