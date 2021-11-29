# Práctica 4. Tu historia de Periodismo de Datos  

## Elección de los datos 

Para realizar los gráficos de esta práctica he escogido los datos del INE sobre [delitos según sexo](https://www.ine.es/jaxiT3/Tabla.htm?t=25998). Como la tabla tenía muchos datos desde la propia página del INE he seleccionado los que me interasaban. Concretamente, he trabajado con los datos de delitos **Contra el patriomonio y el orden socioeconómico**, en el periodo de 2015 a 2020. Mi elección se basa en la curiosidad por indagar en este tema, pues no estoy muy familiarizada con él y, tal y como me esperaba, las cifras son bastante reveladoras.

## Gráfico 1
 
![Gráfico 1](https://github.com/luciamame/uc3m-periodismo-datos/blob/main/img/delitos-a%C3%B1o.png) 

Para este primer gráfico he descargado la selección de **Delitos contra el patrimonio y el orden socioeconómico**, en el periodo de 2015-2020, teniendo en cuenta solo el total, es decir, sin escoger **Hombres** y **Mujeres** desde la página web del INE. Una vez descargado, he abierto el programa Open Refine. Como los datos ya aparecían en forma de tabla no he tenido que cambiar nada antes de empezar a crear el proyecto. 
Una vez hecho esto, he eliminado las columnas 7, 8, 9 y 10 porque no me hacían falta. También he ido seleccionando con la estrellas las filas que o bien estaban vacías, o bien no necesitaba. Para hacer esto, he pinchado en la cabecera de la primera columna (**Alll**) y he puesto facet by star para poder borrar los datos que no necesitaba. 
Por otra parte, he renombrado las columnas 2, 3, 4, 5 y he dado a cada una de ellas una año, desde 2015 a 2020. Igualmente, la columna 1 tenía el nombre de **Resultados Nacionales** y yo lo cambié por **Delitos contra el patrimonio y el orden socioeconómico**. 
Finalmente, he exportado el documento y lo he abierto en Excel puesto que no sabía cómo hacer los cambios que quería en Open Refine. Lo que he hecho en Excel ha sido eliminar las filas de *Total* porque en ellas había espacios en blanco. Para ello, he puesto directamente la cifra de totales bajo las columnas de su año correspondiente y junto al título da cada tipo de delito. De esta manera logré deshacerme de todos los huecos en blanco. 
Tras hacer esto, he subido mis datos a Datawrapper, donde he jugado con varios gráficos y visualizaciones hasta encontrar la que consideraba más adecuada para mis datos: 

- Tipo de gráfico &rarr; 
He escogido un gráfico de sectores múltiple. Cada uno de ellos corresponde a un año distinto. De bajo del año al que pertenecen he creido oportuno poner el totla de delitos contra el patrimonio cometidos en cada uno de los años para que quienes lo vean puedan darse cuenta, a simple vista, de de la diferencia entre unos y otros. 
Cada fragmento pertenece a un tipo concreto de delito: Hurtos, Usurpación, Robos, ... Además, dentro de cada "queso" aparecen el porcentaje de ese delito sobre el total de los cometidos en cada año. Así, quienes consulten el gráfico pueden evidenciar facilmante cómo es la tendencia de cada tipo de delito en este periodo de tiempo. También cuales son los más y los menos cometidos.
 
- Elección de colores &rarr; 
En cuanto a la elección de colores, me he decantado por una escala cromática de rojos, puesto que es un color que se suele relacionar con la violencia y con lo prohibido. Basicamente, he ido cambiando los colores de la escala gradualmente para que todos sigan la misma gama cromática y que la diferenciación no sea drástica, pero de manera que no se confundan entre ellos. 
 
Finalmente,decir que la herramienta Dattawrapper me ha complicado un poco la realización de este gráfico ya que en los gráficos de sectores no he podido poner todos los datos por separados. 3 de ellos se encuentran reunidos bajo la etiqueta **Otros ** puesto que si los ponía todos no aparecían los porcentajes ( ni siquiera cuando pinchaba en un queso en concreto) y esto dificultaba la comprensión del gráfico. 

## Gráfico 2 

![Gráfico 2](https://github.com/luciamame/uc3m-periodismo-datos/blob/main/img/tipos-robos-sexos-2020.png)

Para realizar este gráfico, he vuelto a descargar los datos del INE pero esta vez excluyendo el total, porque la primera vez tan solo descargué el total y para este gráfico me interesa saber la diferencia entre **Hombres** y **Mujeres**. Una vez hecho esto, filtro por la faceta texto , puesto que los años no los entiende como cifras. Aunque podría haber cambiado el formato de los años a fecha no me interesaba porque solo iba a necesitar los datos del año 2020. Por eso, filtro y me quedo con los datos de dicho año. Luego, filtro la columna **Tipos de Delito** y elijo las filas de **Robos con fuerza** y **Robos con violencia**. Las dos filas de **Robos** no me interesa porque es simplemente la suma de **Robos con fuerza** y **Robos con violencia** por un lado en hombres y por otro en mujeres. El "problema" ahora es que las filas **Robos con fuerza** y **Robos con violencia** están duplicadas, puesto que una cuenta los hombres y la otra a las mujeres. Por esto exporto los datos y los abro con Excel. Allí lo que hago es poner los datos de hombres y mujeres bajo el tipo de robo correspondiente.
Luego, ya en Datawrapper, escojo el gráfico de donuts múltiple:
 
- Tipo de gráfico &rarr; 
Considero que este diseño es una buena elección para represaentar estos datos ya que se puede apreciar de manera muy clara la diferencia entre un tipo de robo y otro según cada sexo. Además, preferí poner la cifra en lugar de los porcentajes porque visualmente ambos gráficos son muy parecidos pero lo cierto es que el porcentaje de mujeres que fueron condenadas por robo el pasado año es notablemente inferior al de los hombres condenados por este mismo delito. Por esto mismo también me decidí a poner el total, que no tuve que calcular porque Datawrapper te lo da automáticamente. A pesar de ser un gráfico muy sencillo, creo que evidencia los datos a los que se refiere de manera clara. 

- Elección de colores &rarr; 
En este caso, he decidido arriesgar y escoger dos colores bastante chocantes, e incluso violentos. No obstante, la elección puede justificarse con el tema de los datos, pues se refieren a robos con fuerza y con violencia. Para los robos con violencia he optado por un color gris oscuro mientras que para los robos con violencia he optado por un rojo granate para representar, precisamente, la violencia. 

## Gráfico 3 

![Gráfico 3](https://github.com/luciamame/uc3m-periodismo-datos/blob/main/img/grafico-datos.png) 

Al realizar el gráfico anterior quedé muy sorprendida con la enorme diferencia que hay entre mujeres y hombres en el delito de robo, concretamente en el subtipo de robos con violencia. Por ello decidí hacer un gráfico que reflejara la evolución de este tipo de robos, por sexo, en el periodo de 2015 a 2020. 
Para ello utilicé los datos anteriores, que ya tenía en Open Refine. Quité la faceta de texto 2020 y ordené dicha columna mediante la herramienta sort. Desde dicha pestaña puse que los números de la columna eran fechas y que las quería ordenar de más antiguas a menos. Por otra parte, filtré la columna de delitos para quedarme simplemente con los datos de **Robos con violencia**. Tras hacer esto, los datos estaban listos para ser exportados. 
Una vez descargado el archivo, en Excel agrupé los datos tanto de hombres como de mujeres según el año ya que en Open Refine me aparecía cada año dos veces, una vez en hombres y otra en mujeres. Cuando ya estaban ordenados empecé a diseñar en Datawrapper: 

- Tipo de gráfico &rarr; 
En esta ocasión elegí un gráfico de barras agrupadas. Encima de cada año hay dos barras, una representa a los hombres que han cometido este delito en dicho año y otra a las mujeres. Lo cierto es que es muy sencillo pero de un solo vistado se puede evidenciar la difrencia tan grande en el número de hombres y mujeres que cometen este delito y, a suveces, cómo han hido cambiando estas cifras a lo largo de estos seis años. 

- Elección de colores &rarr; 
Basicamente he escogido el color azul para representar a los hombres y un color rosado para representar a las mujeres. A pesar de que esto sea sexista (al menos para mi) lo cierto es que para quienes vean el gráfico es muy sencillo relacionar el azul con los hombres y el rosa con las mujeres. 

 Creo que esta práctica me ha servido para experimentar tanto con Open Refine como con Datawrapper. Ambas herramientas se pueden utilizar en otras asignaturas y son bastante útiles si pretendes hacer un visualización de datos. 
