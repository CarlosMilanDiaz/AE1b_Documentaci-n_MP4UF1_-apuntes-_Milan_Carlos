# AE1b_Documentaci-n_MP4UF1_-apuntes-_Milan_Carlos

###### Aplicación :GITHUB

Creamos cuenta de github y descargamos en instalamos el GIT (https://git-scm.com/download/win).

Cada vez que queramos crear una nueva carpeta para subir archivos, debemos ir a mis repositorios, new repository, y en el menú pondremos el nombre que queramos ponerle, a continuación vamos al cmd del git(boton windows y escribimos git) y dentro vamos a la carpeta donde queramos guardar las carpetas, es decir hacemos un cd y nos situamos en el disoc duro c por ejemplo

Repositorio de apuntes y todo

Seguidamente entramos a la carpeta que queramos subir o donde queramos clonar una del github.

Si es clonar escribimos Git clone (link que cogemos de la web)

Si queremos subir actualizaciones primero vamos dentro de la carpeta y hacemos:
1.  git init
2.  git add .
3.  git commit -m "comentario que queramos"
4.  git push origin main 

###### Primer capitulo: MARKDOWN

Formatos de texto
Segun como se ponga los asteriscos* o los guinesbajos_ se pondrá en cursiva o en negrita.
Este texto está en *cursiva*
Este texto está en _cursiva_
Este texto está en **cursiva**
Este texto está en __cursiva__
y de esta forma en negrita y cursiva simultaneamente
Este texto está en **_negrita y cursiva_**
De las siguientes "sintaxis" se hacen las listas
ol
1. Primera opción de menú
2. Segunda opción de menú
3. Tercera opción de menú
UL
* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primer submemú
    2. Segundo submenú
- Cuarta opción de lista desordenada
    *Tercer submenú
    *Cuarto submenú
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada

Esto de las triple comilla es para que no ejecute el codigo, simplemente que lo enseñe sin que se ejecute el codigo que salga
``` 
<html>
<head>

</head>
<body>
    <p>Esto es un párrafo por eso una "p"
</body>
</html>
```

Así se sube un enlace o link
Lo de dentro de corchetes es el texto que saldrá como link en la página real despues de eso se cierra corchete, luego se abre el parentesis y pones el link donde quieres que se rediriga, y después entre comillas se pone un texto que quieres que salga en la web minetras pongas el raton encima del enlace sin clicar. 
[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

Así se pone una imagen
Para poner imagenes, se pone primero una exclamación, y se abre corchete, lo que hay dentro es un identificador y se cierra corchete, despúes se abre el parentesis y escribes el link de la url de la foto estando subida en la carpeta del github(NO DEL EXPLORADOR DE ARCHIVOS), seguido poner entre comillas un texto que quieres que salga en la web minetras pongas el raton encima del enlace sin clicar.
![Eso es una imagen del rial G Hasbulla](https://github.com/CarlosMilanDiaz/AE1b_Documentaci-n_MP4UF1_-apuntes-_Milan_Carlos/blob/main/One-Piece-Enies-Lobby.jpg "Titulo opcional de la imagen ")


Tablas
La cantidad de columnas se basa en la cantidad de barras como esta "|" que contenga la linea de codigo


|Primera col|Segunda col|Tercera col|


Los textos que están aqui dentro son los titulos de las columnas


|--------------|:------------:|---------:| 


La anchura de la columna se hará segun lo ancho que se ponga con los guiones, y según donde ponga los : definirá si está centrado, a la izquierda o a la derecha.


Tambien se pueden hacer opciones y entre los [] lo utilizamos para seleccionar la opcion que queramos.

 -[ ] Opción A
 
 -[X] Opción B
 
 -[ ] Opción C

###### Segundo capitulo: HTML
En un leguaje de marcas empieza con una etiqueta que se escribe entre <> y para marcar o decir que acaba se escribe la misma etiqueta pero con uns barra delante </>.

La sintaxi basica es, ```<img href = "">``` basicamente es , etiqueta atributo y información del atributo.

Aqui definimos el tipo de pagina que hacemos para decirselo al navegador
```<!DOCTYPE html>```

Aqui definimos el idioma 
```<html lang="en">```

Justo aqui empieza el encabezado de datos
``` <head>```

Esta linea indica el set de caracteres.
```<meta charset="UTF-8">```

Esto simple mente es para el ancho y demas de la pagina
```<meta name="viewport" content="width=device-width, initial-scale=1.0">```

Esta linea de codigo es donde se pone el titulo que saldrá arriba en la pestaña de la pagina1
```<title>Document</title>```

Y aqui acaba el encabezado como siempre acaban las etiquetas de una pagina con la barra"/"
```</head>```
Justo aqui empieza el body, que es el cuerpo de la pagina
``` <body>```
Estas etiquestas són las de un parrafo, el cual se abre sin / y se cierra con ella escrita.
```<p> </p>```

El order list es el una lista ordenada en el que abre con ol, y acaba con /ol, la cual cada elemento interno de la lista es un ```<li>```.

```<ol>
    <li>como este por ejemplo que abre con li, y como todas las etiquetas se cierran con /.</li>
    <li>aqui hay otro elemento de la lista</li>
    <li>y aqui el tercer elemento</li>    
</ol>y ya aqu cerramos el order list```
```
A parte de ol se puede hacer como Unorder list(ul).
O si quiero hacer una lista dentro de otra lista seria lo mismo, haciendo un ol, con la otra lista añadida identada.
Como por ejemplo:
```
<ol>
    <li>
    1
    </li>
    <ol>
        nivel1
    </ol>
    <ul>
        nivel 2
    </ul>
</ol>
```

br es una etiqueta pra dejar un salto o espacio
```<br>```
```<a href="google.com" alt="Por aqui se va a google" target="_blank">aqui dentro va lo que queremos que salga en pantalla</a>```
Esto es texto con un enlace a la pagina que se poga, y se escribe con la etiqueta ```<a href=""></a>```
El alt: srive para poner un texto que aparezca cuando nos ponemos encima del enlace sin clicar
El target_blank: indica que cuando abras/se clique ese enlace, se abra en otra pestaña diferente a en la que se clica de la pagina.

```<hr>``` sirve para poner una linea horizontal 
Esta etiqueta es una cita, (es una frase de alguien ajeno)
```<blockquote></blockquote>```

Para mostrar una imagen es , la etiqueta img, con la ruta de donde se saca la imagen,
```<img src="One-Piece-Enies-Lobby.jpg">```

Para usar un icono de una web como por ejemplo fontawesomehay que linkear en el head el ```<script src="https://kit.fontawesome.com/06d159bd36.js" crossorigin="anonymous"></script>``` Escribimos este link/script que nos ha dado la pagina Para poder enlazar nuestra pagina para enlaza y linkear cosas de esta, como poer ejemplo podriamos poner para poner un icono o una fuente lo siguiente:```<i class="fa-solid fa-dog">codigo enlazado desde fontawesome</i>``` 


Para poner una foto se pone
```<img src="(ubicacion de la foto)" alt="Imgen de planeta">```
Para ir a alguna parte dentro de la propia pagina
Añadir un id a la parte qu queramos ir a ver(el destino)
Añadimos por ejemplo un titulo que queremos que sirva como enlace para ir a ver el destino(origen)

```< h3 id=inicio>```
```<a href="#inicio"><h3>aqui me envia al titulo </h3></a>```
En el  caso que queramos poner una tabla se pone lo siguiente:

```
<table border="2px">
    <thead>
        <tr>
            <th>123</th>
            <th>234</th>
            <th>345</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>qwe</th>
            <th>wer</th>
            <th>ert</th>
        </tr>
    </tbody>
    <tfoot>

    </tfoot>
</table>
```


En el que table es la etiqueta de la tabla general, tr son las filas en la que escribirmos th por cada columna que quieras poner con el dato a mostrar dentro, si quieres puedes poner un thead o tfoot para hacer un encabezado o un pie de tabla, sino si solo se quiere hacer una tabla sin nada mas, se hace en el tbody.
```</body>```
```</html>```

En HTML, los contenedores son elementos que se usan para agrupar otros elementos HTML y organizar el contenido de la página web. Aquí te explico algunos tipos de contenedores más comunes:

Div (división):

html
```<div></div>```
Este es uno de los contenedores más versátiles y comúnmente usados. No tiene un significado semántico específico, por lo que se usa principalmente para aplicar estilos mediante CSS o para agrupar otros elementos.

Contenedores semánticos: A medida que HTML5 se ha desarrollado, se han introducido etiquetas semánticas que mejoran la accesibilidad y el SEO (optimización para motores de búsqueda) al dar un significado claro al contenido. Algunos ejemplos son:

<header>: Define el encabezado de una sección o documento.

<nav>: Representa un conjunto de enlaces de navegación.

<section>: Define una sección en un documento.

<article>: Representa un contenido independiente y autocontenido.

<aside>: Contenido relacionado con el contenido principal, pero que puede ser leído independientemente.

<footer>: Define el pie de página de una sección o documento.

Form:

html
```<form></form>```
Contenedor utilizado para agrupar controles interactivos que permiten a los usuarios enviar datos a un servidor.

Estructura básica de un formulario
Un formulario en HTML se define con la etiqueta <form>. Dentro de esta etiqueta, se colocan varios controles de formulario como entradas de texto, botones de envío, menús desplegables, etc.

Atributos principales de la etiqueta ```<form>```
action: Especifica la URL a la que se enviarán los datos del formulario.

method: Define el método HTTP que se usará para enviar los datos (GET o POST).

Controles de formulario comunes
Campo de texto:

html
```<input type="text" name="nombre">```
Campo de contraseña:

html
```<input type="password" name="contraseña">```
Campo de correo electrónico:

html
```<input type="email" name="email">```
Área de texto:

html
```<textarea name="mensaje">```
Botón de envío:

html

```<input type="submit" value="Enviar">```
