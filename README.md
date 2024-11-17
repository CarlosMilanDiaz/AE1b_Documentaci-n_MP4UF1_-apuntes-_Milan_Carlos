# AE1b_Documentaci-n_MP4UF1_-apuntes-_Milan_Carlos

###### Aplicación :GITHUB

creamos cuenta de github y descargamos en instalamos el GIT (https://git-scm.com/download/win).

cada vez que queramos crear una nueva carpeta para subir archivos, debemos ir a mis repositorios, new repository, y en el menú pondremos el nombre que queramos ponerle, a continuación vamos al cmd del git(boton windows y escribimos git) y dentro vamos a la carpeta donde queramos guardar las carpetas, es decir hacemos un cd y nos situamos en el disoc duro c por ejemplo

Repositorio de apuntes y todo

Seguidamente entramos a la carpeta que queramos subir o donde queramos clonar una del github.

si es clonar escribimos Git clone (link que cogemos de la web)

si queremos subir actualizaciones primero vamos dentro de la carpeta y hacemos:
1.  git init
2.  git add .
3.  git commit -m "comentario que queramos"
4.  git push origin main 
###### Primer capitulo: MARKDOWN

formatos de texto
Segun como se ponga los asteriscos* o los guinesbajos_ se pondrá en cursiva o en negrita.
Este texto está en *cursiva*
Este texto está en _cursiva_
Este texto está en **cursiva**
Este texto está en __cursiva__
y de esta forma en negrita y cursiva simultaneamente
Este texto está en **_negrita y cursiva_**

de las siguientes "sintaxis" se hacen las listas
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

esto de las triple comilla es para que no ejecute el codigo, simplemente que lo enseñe sin mas
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
lo de dentro de corchetes es el texto que saldrá como link en la página real despues de eso se cierra corchete, luego se abre el parentesis y pones el link donde quieres que se rediriga, y después entre comillas se pone un texto que quieres que salga en la web minetras pongas el raton encima del enlace sin clicar. 
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
