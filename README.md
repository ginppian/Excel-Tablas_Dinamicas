Tablas Dinámicas
==============

## Definición

<p align="justify">
Las tablas dinámicas o tablas pivote son un excelente modo de resumir, analizar, explorar y presentar los datos.
</p>

## Condiciones

<ul>

<li>
<p align="justify">
Los datos deben organizarse en formato tabular y no tener ninguna fila o columna en blanco. Lo ideal es que pueda usar una tabla de Excel.
</p>
</li>

<li>
<p align="justify">
Si se agregan filas a la tabla se tendrá que actualizar manualmente el rango de origen de datos o usar una fórmula de rango dinámico con nombre.
</p>
</li>

<li>
<p align="justify">
Los tipos de datos de columnas deben ser iguales.
</p>
</li>

<li>
<p align="justify">
Las tablas dinámicas trabajan en una instantánea de los datos, denominada caché, por lo que los datos reales no se modifican de ninguna forma.
</p>
</li>

</ul>

## Material Apoyo

<p align ="justify">
<a href="https://github.com/ginppian/Excel-Tablas_Dinamicas/raw/master/MaterialApoyoTablasDinamicas.xlsx">Ejercicio</a>
</p>

<p align="center">
	<img src="https://github.com/ginppian/Excel-Tablas_Dinamicas/blob/master/img/img1.png" width="687" height="385">
</p>

## Desarrollo

### Filtros

<p align="justify">
Los filtros nos permiten buscar subconjuntos de un conjunto de datos de una columna, este filtro afectará toda la columna.
</p>


<b>Pasos</b>

<ol>
	
<li>
<i>Seleccionamos la tabla:</i>
<p>	
	Pulsando <i>CTRL + SHIFT + SPACE</i>
</p>
<p>
	PS: Podríamos seleccionar sólo los títulos o cabeceras de la tabla.
</p>
</li>

<li>
<i>Generamos filtros:</i>
<p>
Vamos a la ficha <i>DATOS</i> en el grupo "Ordenar y filtrar" seleccionamos <i>FILTRO</i>.
</p>

<p>
	PS: En la ficha <i>INICIO</i> podríamos seleccionar <i>DAR FORMATO COMO TABLA</i>. 
</p>
</li>

</ol>

<p align="center">
	<img src="https://github.com/ginppian/Excel-Tablas_Dinamicas/blob/master/img/img2.png" width="831" height="350">
</p>

<b>Desventajas:</b>

<p align="justify">
Los <i>filtros</i> sólo <b>ocultan</b> los valores de la tabla no generan una nueva tabla, a diferencia de las tablas dinámicas.
</p>

### Tabla Dinámica

<ol>	

<li>
<i>Región</i>
<p align="justify">
Seleccionamos toda la región incluyendo títulos/cabeceras de la tabla o nos posicionaros dentro de la tabla y Excel reconocerá automáticamente la región cuando insertemos la tabla dinámica.</p>
</li>

<li>
<i>Insertar</i>
<p align="justify">
Ya seleccionado la región nos vamos a: <i>INSERTAR</i> y en el grupo "Tablas" seleccionamos <i>TABLA DINÁMICA</i> y nos mostrará algo como:
</p>
<p align="center">
<img src="https://github.com/ginppian/Excel-Tablas_Dinamicas/blob/master/img/img3.png" width="943" height="500">
</p>
</li>

<li>
<i>Implementación</i>
<p align="center">
<img src="https://github.com/ginppian/Excel-Tablas_Dinamicas/blob/master/img/img4.png" width="1220" height="400">
</p>
</li>

</ol>

## Fuente
<p align="justify">
<a href="https://support.office.com/es-es/article/Crear-una-tabla-din%C3%A1mica-para-analizar-datos-de-una-hoja-de-c%C3%A1lculo-a9a84538-bfe9-40a9-a8e9-f99134456576">Tablas Dinámicas Microsoft</a>
</p>

<p align="justify">
<a href="https://www.youtube.com/watch?v=AIipB0FFw7Y&t=1s"
</a>
</p>
