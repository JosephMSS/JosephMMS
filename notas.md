# Orden básico de etiquetas
## 1. La Estructura de la Cabecera
* >```<header></header>``` Este es el contenedor de la cabecera.
* >```<nav></nav>``` Se utiliza para la creación de la barra de navegación.
* > ```<ol></ol> | <ul></ul>``` Creación de una lista 
* >  ```<li><li>``` Creación de los items
* >  ```<a><a>``` Para crear una hipertexto
## Contenido de la Página
* > El contenido de la página debe llevar al menos un ```<h1></h1>```
* >```<section></section>``` Esta se puede llevar a cabo por medio de sectores en vez de utilizar la etiqueta ```<div></div>```
* > La etiqueta ```<article></article>``` **<spam style="color:red">Ver en que caso lo usa</spam>**


```!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curso de Desarrollo Web</title>
</head>
<body>
    <header>  Cabecera
        <nav> barra de navegacion
            <ol> para lisatar las paginas a las cuales nos vamos a dirigir
                <li>
                    <a href=""></a>
                </li>
            </ol>
        </nav>
    </header> fin d ela cabecera
    <section>Principal</section> cuerpo de la pagina
    <footer>footer</footer> el pie de la pagina
</body>
</html> ```