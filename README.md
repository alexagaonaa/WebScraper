<h1 align="center"> :lipstick: Proyecto final: Web Scraper de maquillaje </h1>
<b> <blockquote> Integrantes del equipo: </b> <br>
<li>Gaona Amaya Silvia Alexa - https://github.com/alexagaonaa <br>
<li>León Morales Guadalupe - https://github.com/guadalupe30 </blockquote>

<h2 align="center"> :pencil2: Descripción del proyecto </h2>
Este proyecto consiste en la creación de un Web Scraper, que es un programa que tiene como finalidad extraer información de sitios web. En este caso en específico, nuestro proyecto tiene como finalidad extraer ciertos datos de sitios de maquillaje para poder hacer una comparación de tipo gráfica, y facilitar la lectura al usuario.

<h2 align="center"> :ballot_box_with_check: Pre-requisitos </h2>
<i> Para poder ejecutar nuestro proyecto necesitas: </i>
<li> Python
<li> Anaconda (para poder instalar con mayor facilidad las librerías)
<li> JupyterLab (para poder correr el código con un formato visualmente más ordenado)
<li> Un chrome driver según la versión de Google Chrome que tengas instalada
<li> Google Chrome

<h2 align="center"> :file_folder: Funcionalidades del proyecto </h2>
<li>Recolectar datos específicos (nombre y precios) de las páginas: Bellísima, Liverpool y Vorana.
<li>Crear un dataframe por sitio con la información recolectada.
<li>Convertir cada uno de los dataframes en archivos .csv para facilitar la lectura de ellos.
<li>Concatenar todos los dataframes en uno solo para poder comparar los precios de los diferentes productos en cada sitio.
<li>Se importan las librerias pertinentes para poder realizar consultas de SQL.
<li>Crear gráficas comparando los precios promedio de cada producto en cada sitio web.
<li>Crear una gráfica final comparando todos los precios promedio de todos los productos en los 3 sitios web.

 <h2 align="center"> :interrobang: ¿Cómo ejecutar el proyecto? </h2>
 <ol>
 <li> Instalar las paqueterías necesarias usando la terminal de anaconda
 <li> Descargar el web driver (en este caso el chrome driver correspondiente a la versión instalada de chrome)
 <li> Abrir el archivo .py en alguna terminal como spyder, o abrir el archivo .ipynb en JupyterLab
 <li> Cambiar la ubicación del chrome driver, según donde la hayas descargado
 <li> Si gustas cambiar los productos que buscará el Web Scraper, encontrarás algunas variables llamadas "Producto1, "Producto2", y así hasta el "Producto5"
 <li> Listo, ahora sólo queda correr las líneas restantes del código, y este se encargará de crear: 
 <ol> <li>Tres archivos .csv (uno por cada sitio web) que rellenará con la información correspondiente de los 5 productos buscados.
 <li> Un archivo .csv donde recolectará toda la información de los 3 sitios web
 <li> Cinco gráficas(una por cada producto) donde se compara el precio promedio del producto en los 3 sitios web
 <li> Una gráfica donde se compararán los precios promedios de todos los productos en los 3 sitios web.
 <li> También tendrás la oportunidad de hacer consultas SQL al tener el dataframe final y la librería pandasql.
 
