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
