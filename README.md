# Ánalisis espacial radiacion en colombia
<h4>¿qué encontraras aquí ?</h4>
Encontraras un analisis exhaustivo del comportamiento de la radiación solar a lo largo del territorio colombiano utilizando tecnicas de geoestadistica, como lo es el ajuste de varios semivariogramas escogiendo la mejor opción, análisis de tendencias espaciales, analisis de isotropia y descripción gráfica, resultados que mostraremos acontinuación, los pasos tecnicos se omiten aquí pero estan bien documentados en el código, tambien encontraras los mapas y los datos para poder replicar los resultados aaquí expuestos. 

<h4>Observaciones</h4>
 119 observaciones de los kilowatts por hora recibidos en cada una de las locaciones   a lo largo del territorio nacional en julio de 2020.. 

![alt text](https://i.imgur.com/o7iqwIG.png)

<h4>Predicciones</h4>
  Para realizar las predicciones via krigging espacial se decidió utilizar un modelo para el semivariograma del tipo Wave, con parametros psill = 0.065,
                  range = 250000,nugget = 0.36, podemos ver los resultados graficamente, donde es claro que la costa atlantica recibe en promedio mayor radiación que el centro y sur occidente del pais, lamentablemente por la falta de observaciones en el sur del pais nuestras preddiciones en ese lugar no son confiables. 

  ![alt text](https://i.imgur.com/ZBiK0LE.png)
  
  <h4>Variana de las predicciones</h4>
  Ahora observemos la varianza de nuestras predicciones. 
  
  ![alt text](https://i.imgur.com/8g9EZXp.png)
  
  

