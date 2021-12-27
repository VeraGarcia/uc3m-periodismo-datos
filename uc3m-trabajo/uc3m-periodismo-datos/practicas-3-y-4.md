# Prácticas-3-y-4-

## Introducción
El objetivo del presente ejercicio radica en expresar una serie de datos por medio de gráficos que permitan una mejor visualización de los datos y que conviertan una serie de números más bien abstractos en una representación mucho más concreta. Así pues, para la elaboración de las prácticas que nos ocupan, se han utilizado una serie de aplicaciones adecuadas a cada uno de los pasos que se han venido siguiendo hasta llegar al resultado final, presentado en este repositorio. 

## Justificación de la elección de esta base de datos
En principio, la base de datos elegida -"Deportistas de alto nivel en Castilla y León"- contaba con los siguientes parámetros: año, fecha de registro, federaciones deportivas Castilla y León, procedimiento, grupo, apellidos, nombre, desestimación, causa desestimación y detalle desestimación. A priori, parecía ser un data set que determinaba si los candidatos presentados eran reconocidos como deportistas de alto nivel o no en función de sus logros deportivos; es por esto que me resultó interesante descartar los datos relativos a quienes no habían sido reconocidos como tal para centrarme así en quienes habían entrado a formar parte de la nomenclatura de "deportistas de alto nivel". A partir de ahí, traté de purgar los datos que no me interesaban para así poder realizar las gráficas que, por el contrario, sí me resultaban atractivas de interpretar. 

## Aplicaciones y modo de proceder
En primer lugar, la base de datos .csv se ha trasladado a OpenRefine, donde de más de 500 celdas se ha pasado a 319. Se han desestimado los datos relativos a las solicitudes que habían sido denegadas y, con las aceptadas, se ha elaborado una clasificación en función de los distintos deportes que practican las personas contabilizadas. También se ha utilizado Excel (aplicación de Microsoft) con el fin de pulir, por medio de una serie de fórmulas y formatos condicionales, algunos detalles mínimos concernientes a datos myt concretos. Asimismo, se han segregado las crifras relativas a las diferentes categorías que aparecían en la base de datos inicial, siendo estas: deportista, entrenador/a y juez/árbitro. 
Una vez tenemos los datos con los que nos disponemos a trabajar, pasamos a DataWrapper, una aplicación cuya finalidad radica en dar forma a las tablas que le son dadas desde otras plataformas. Su accesibilidad es adecuada y cuenta con diversas funciones para modificar la apariencia de los esquemas que produce; lo más positivo, a mi modo de ver es que la sencillez no actúa en detrimento de la calidad de sus funciones, lo que la convierte en una aplicación asequible a la par que íntegra. 
Por último y tras haber elaborado las tablas deseadas con sus correspondientes representaciones, estas han sido importadas a GitHub para entrar así a formar parte de la presente explicación. 

## Segregación por sexos 
! [alt text](https://github.com/mgreciano/Imagen-1/blob/main/Sexos%20alto%20nivel.png)

Para este primer gráfico, se han separado los datos mediante una selección de los nombres femeninos y masculinos y una posterior separación de ambos grupos con el fin de observar la presencia de un género y otro entre las categorías de alto nivel. Los hombres tienen un 26% más de representación que el sector de las mujeres dentro de este ámbito, lo cual puede dar lugar a un proceso de reflexión: ¿qué es lo que falla en el ámbito deportivo para que las mujeres tengan una presencia tan por debajo del sector masculino? La elaboración de este gráfico tiene su justificación en una demostración de lo necesario que resulta encontrar más referentes entre las niñas para que en ellas cale la idea de que también pueden optar por una carrera deportiva y remar así hacia la senda de la igualdad real, también en el deporte. 
La elección del gráfico de sectores se justifica en que este tipo de representaciones resulta muy práctico a la hora de expresar proporciones y cuánto contribuye cada una de las partes al total, lo cual se corresponde exactamente con la intencionalidad anteriormente descrita. La selección de los colores se ha llevado a cabo de acuerdo con los estereotipos 

## Categorías 
! [alt text](https://github.com/mgreciano/Imagen-2/blob/main/nG4uj-categor-as-de-alto-nivel.png) 

De la misma forma que el anterior, por medio de un gráfico sectorial se representan aquí los distintos tipos de cargos que encontramos entre los denominados "de alto nivel" en la provincia de Castilla y León. Como es evidente, la mayor parte de este compendio de personas dedicadas al deporte está configurado por los propios deportistas, quienes representan casi un 85% del total. En menor medida, encontramos también entrenadores y jueces y árbitros. En este caso, se ha optado por el empleo de tonalidades verdosas por tratarse de un color ligado a la naturaleza y a la salud, dos factores íntimamente ligados a la práctica deportiva. 

## Tipo de participación
! [alt text](https://github.com/mgreciano/Imagen-3/blob/main/Tipo%20de%20participaci%C3%B3n%20alto%20nivel.png)

En este tercer caso, se busca establecer una comparación entre la cantidad de deportistas que se dedican a deportes colectivos frente a quienes lo hacen de manera individual, razón por la cual la representación elegida ha sido una gráfica con dos barras. El color se ha seleccionado de manera arbitraria, obedeciendo así a una mera preferencia estética. Aunque no se precisa con total exactitud el número de personas que se dedican a cada modalidad, sí se puede apreciar cómo los deportes individuales sobrepasan a los que se juegan por grupos. 

## Deportes utensilios: pelota
! [alt text](https://github.com/mgreciano/Imagen-4/blob/main/Deportes%20con%20pelota%20alto%20nivel.png)

En última instancia, se ha elaborado una representación para medir los deportes en los que se utiliza pelota y en los que no. Con este gráfico de barras horizontales en color naranja (tonalidad que resulta de lo más vigorizante y asociada a la actividad física, siendo esta bastante menos agresiva que la roja), se puede ver cómo el fútbol y el rugby son los dos deportes que cuentan con mayor número de participantes. Cada una de las barras aparece correspondientemente sombreada para mostrar de manera más clara hasta qué punto llega cada una. 

## Conclusión del ejercicio

En líneas generales, las conclusiones que saco de estas prácticas es que las aplicaciones utilizadas para llevarlas a cabo cumplen a la perfección con sus funciones. La que me ha resultado más útil de las dos ha sido, sin duda alguna, Datawrapper, puesto que me ha parecido de lo más práctica y sencilla, mientras que OpenRefine se me ha complicado un poco más en tanto que no es tan intuitiva, aunque una vez se va aprendiendo a utilizar, se convierte en una buena herramienta para manejar grandes amalgamas de datos. A mi parecer, la función de las facetas de OpenRefine es la que más curiosa y completa en sus funciones.
