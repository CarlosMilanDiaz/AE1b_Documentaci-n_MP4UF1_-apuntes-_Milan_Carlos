###Aplicación: GITHUB

Creamos una cuenta de GitHub y descargamos e instalamos Git desde: https://git-scm.com/download/win.

Crear nuevo repositorio

Cada vez que queramos subir archivos:

Ir a "Mis repositorios" y hacer clic en "New Repository".

Elegir un nombre para el repositorio.

Abrir Git Bash (buscar "git" en el menú de inicio).

Navegar a la carpeta deseada usando cd (por ejemplo, cd C:/mis-proyectos).

Clonar o subir archivos

Para clonar un repositorio: git clone <link_del_repo>

Para subir actualizaciones:

git init
git add .
git commit -m "comentario que queramos"
git push origin main

###Capítulo 1: MARKDOWN

Formatos de texto

Texto en cursiva → *Texto* o _Texto_

Texto en negrita → **Texto** o __Texto__

Texto en cursiva y negrita → **_Texto_**

Listas

Ordenadas (ol):

1. Opción uno
2. Opción dos

Desordenadas (ul):

* Elemento
- Elemento
+ Elemento

Listas anidadas:

- Opción principal
  - Subopción
    1. Sub-subopción

Código

Usar triple comilla invertida para mostrar código sin ejecutarlo:
```
<html>
  <head></head>
  <body>
    <p>Esto es un párrafo</p>
  </body>
</html>
```
Enlaces e imágenes

[Texto del enlace](http://ejemplo.com "Texto emergente")
![Alt text](https://ruta.de.la.imagen.jpg "Texto emergente")

Tablas

| Columna 1 | Columna 2 | Columna 3 |
|:--------- |:---------:| ---------:|
| A        | B         | C         |

Checkbox

- [ ] Opción A
- [X] Opción B

###Capítulo 2: HTML

Estructura básica
```
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
  </head>
  <body>
    <!-- Contenido aquí -->
  </body>
</html>
```
Elementos comunes
```
<p>: párrafo

<br>: salto de línea

<hr>: línea horizontal

<a href="">Texto del enlace</a>

<img src="imagen.jpg" alt="Descripción">

<blockquote>: cita textual
```
Listas:
```
<ol><li>Item</li></ol>
<ul><li>Item</li></ul>
```
Tablas:
```
<table border="1">
  <thead>
    <tr><th>Col 1</th><th>Col 2</th></tr>
  </thead>
  <tbody>
    <tr><td>Dato 1</td><td>Dato 2</td></tr>
  </tbody>
</table>
```
Contenedores
```
<div>: contenedor genérico
```
Semánticos: <header>, <nav>, <section>, <article>, <aside>, <footer>

Formularios
```
<form action="" method="POST">
  <input type="text" name="nombre">
  <input type="password" name="clave">
  <input type="email" name="correo">
  <textarea name="mensaje"></textarea>
</form>
```
###Capítulo 3: CSS

¿Qué es CSS?

CSS (Cascading Style Sheets) permite definir el estilo y formato de los elementos HTML. Controla colores, márgenes, tamaños, posiciones, etc.

Formas de incluir CSS

En línea:
```
<p style="color: red;">Texto en rojo</p>
```
En la cabecera (dentro del HTML):
```
<head>
  <style>
    p { color: blue; }
  </style>
</head>
```
Archivo externo:
```
<link rel="stylesheet" href="styles.css">
```
Selectores básicos
```
h1 { color: navy; }
#idEjemplo { font-size: 20px; }
.claseEjemplo { background-color: yellow; }
```
Propiedades comunes
```
color, background-color

font-size, font-family

margin, padding, border

display, position, flex

Box Model

Cada elemento tiene:

Contenido

Padding (espacio interno)

Borde

Margin (espacio externo)
```
###Capítulo 4: Diseño Responsive

¿Qué es el diseño responsive?

Es una técnica para que las páginas web se adapten a distintos tamaños de pantalla (PC, tablet, móvil).

Unidades relativas
```
%, em, rem, vw, vh
```
Media Queries

Permiten aplicar estilos según el tamaño del dispositivo:
```
@media (max-width: 768px) {
  body {
    font-size: 14px;
  }
}
```
Flexbox (layout flexible)
```
.container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
```
Grid (layout en rejilla)
```
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}
```
Buenas prácticas

-Usa un viewport adecuado: <meta name="viewport" content="width=device-width, initial-scale=1.0">

-Prueba en diferentes dispositivos o usa herramientas como el inspector de Chrome.

-Usa frameworks como Bootstrap si necesitas componentes listos para usar.
