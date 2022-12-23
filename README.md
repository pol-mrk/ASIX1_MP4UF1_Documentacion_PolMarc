# ASIX1_MP4UF1_Documentacion_PolMarc

# Markdown
### Encabezados
* H1 (#)
* H2 (##)
* H3 (###)
* H4 (####)
* H5 (#####)
* H6 (######)

### Estilos de letra
*Itálica / cursiva*: (*texto* / _texto_)

**Negrita**: (**texto** / __texto__)

**anidar _estilos_**: (**palabra1 _palabra2_**)

### Listas
**Ordenadas**
1. Primer elemento de la lista
2. Primer elemento de la lista
  (El número de orden no ha de ser necesariamente consecutivo)
  Tabulación→ 1. Elemento de sublista ordenado

**Desordenadas**
* Elemento de lista desordenada (*)
- Otro elemento de lista desordenada (-)
+ Otro elemento de lista desordenada (+)
   (Se puede elegir cualquiera de los tres símbolos para crear una lista desordenada)
   Tabulación→ * Elemento de sublista desordenado

### Párrafos
Para crear un bloque de texto nuevo (etiqueta), se introduce una línea en blanco.

### Código
El código se ha de incluir entre acentos graves (`)`. Si en el código aparece un acento grave, se ha de introducir el carácter dos veces al principio de la sección del código.

``Todo esto es `código`.``

También se puede marcar el área correspondiente al código insertando tres acentos graves al principio y al final. Junto a los tres iniciales se puede indicar el lenguaje (HTML, JavaScript) para que incluso se muestre con los colores adecuados:

```html
<html>
  <head>
  </head>
</html>
```

### Enlaces
[Link] ](https://ejemplo.com/ "Título opcional del enlace")
  a) Primero se incluye el texto del link entre corchetes y posteriormente el link entre paréntesis).    
  b) El “título opcional del enlace” es el texto alternativo al pasar el ratón por encima.

### Imágenes
Inline-style: 
![alt text](https://github.com/img/icon48.png "Título opcional de la imagen")

Reference-style: 
![alt text][logo]
[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

### Tablas
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

  a) Los dos puntos se usan para alinear las columnas (izquierda, centrado, derecha).
  b) No es necesario que estén alineadas verticalmente. Solo a nivel visual para claridad del código.
  c) Se han de poner al menos tres guiones para separar cada encabezado

### Notas al pie de página
Texto con enlace a nota de pie de página [^1]

[^1]: Aquí encuentras el texto de la nota al pie de página.

### Listas de verificación
- [ ] A
- [x] B
- [ ] C
  (Dejar un espacio en blanco entre los dos corchetes en las que aparezcan vacias)

# HTML
## Encabezados
```
  <h1>el más grande</h1>
  <h2>menos grande</h2>
  <h3>normal</h3>
  <h4>medio</h4>
  <h5>pequeño</h5>
  <h6>más pequeño</h6>
```
<h1> el más grande (h1) </h1>
<h2> menos grande (h2) </h2>
<h3> normal (h3) </h3>
<h4> medio (h4) </h5>
<h5> pequeño (h5) </h5>
<h6> más pequeño (h6) </h6>

## Divisores
Un divisor (div) sirve para dividir la página por partes separadas entre sí, cada divisor que pongamos dividirá la página en secciones. Si cambiamos alguna propiedad css del divisor, solo afectará al contenido de dentro de este.
```
<div>
  <h1>Contenido del div</h1>
</div>
```
## Span
Un span sirve para agrupar elementos dentro de un contenedor o para aplicar estilos a un fragmento de texto.
```
  <p>Este es un <span style="color: red;">párrafo</span> con una palabra resaltada</p>
```
## a
Es un elemento que se utiliza para crear un enlace a otra página web.
```
<a href="https://ejemplo.com">Texto del enlace</a>
```
También se utiliza para enlazar una sección específica de una página.
```
<a href="#seccion1">Ir a la sección 1</a>

<!-- contenido de la página -->

<h2 id="seccion1">Sección 1</h2>

```
## Párrafo y formato de texto
### p
Es un elemento que sirve para crear un parágrafo
```
<p> Esto es un parágrafo </p>
```
### Formato
Le vamos a dar formato para **resaltar**, <u>subrayar</u> o poner en *cursiva* un texto.
```
<p><b>Texto resaltado</b></p>
<p><u>Texto subrayado</u></p>
<p><i>Texto en cursiva</i></p>
```
## Listas
Crearemos las listas con el elemento li:
```
<li>
  <p>Aquí irá el tipo de lista</p>
</li>
```
Podemos hacer listas ordenadas o desordenadas.
### ul
Esta es la lista desordenada:
```
<li>
  <ul>Elemento desordenado 1</ul>
  <ul>Elemento desordenado 2</ul>
  <ul>Elemento desordenado 3</ul>
</li>
```
### ol
Esta es la lista ordenada:
```
<li>
  <ol>Elemento ordenado 1</ol>
  <ol>Elemento ordenado 2</ol>
  <ol>Elemento ordenado 3</ol>
</li>
```
## Saltos de línea
Se utiliza para insertar un salto de línea o una nueva línea en un documento HTML.
```
Este texto está en la misma línea.
<br>
Este texto está en una línea diferente.
```
## Línea de separación
Es un elemento de contenido que se utiliza para insertar una línea horizontal en un documento, así lo divide en secciones.
```
<h1>Título de la sección</h1>
<p>Texto de la sección</p>

<hr>

<h1>Título de la siguiente sección</h1>
<p>Texto de la siguiente sección</p>
```

## Media
### Imagen
Para añadir una imagen utilizaremos la etiqueta `<img>` e introduciremos el enlace o ruta de esta imagen.
```
<h1>Título de la sección</h1>
<p>Texto de la sección</p>

<hr>

<h1>Título de la siguiente sección</h1>
<p>Texto de la siguiente sección</p>
```
### Vídeo
Añadiremos un vídeo con la etiqueta `<video>` e introduciremos el enlace o ruta de este.

# CSS
## Selectores
### *
Este elemento se utiliza como un comodín para seleccionar todos los elementos de un documento HTML.
```
* {
  margin: 0;
  padding: 0;
}
```
Esto aplicaría la regla de margin y padding con un valor de 0 a todos los elementos del documento.
### .(nombre clase)
Las clases son atributos que se pueden asignar a elementos HTML para diferenciarlos de otros elementos y aplicar estilos a ellos.
```
.error {
  color: red;
}

.warning {
  background-color: yellow;
}
```
Estas son las clases con los atributos que afectarán al elemento HTML con esa classe.
```
<p class="error warning">Este párrafo tiene las clases "error" y "warning" y se verá en rojo y con un fondo amarillo.</p>
```
Este es el elemento HTML afectado por las clases que le hemos definido anteriormente en el CSS.
### #(nombre ID)
Los identificadores hacen la misma función que la clase, pero estos empiezan por "#" en vez de ".".
```
#header {
  background-color: blue;
}
```
Para seleccionar un elemento con un ID específico en CSS, se debe utilizar el símbolo "#" seguido del nombre del ID.
```
<div id="header">Este es el encabezado de la página.</div>
```
Para asignar un ID a un elemento HTML, se debe utilizar el atributo "id" y asignarle un valor único.
## Propiedades CSS
### Texto y fuente
```
font-family: 'Nunito', sans-serif;
```
Esta propiedad sirve para cambiar la fuente del texto, y el valor define la fuente que queremos asignar al texto.
```
font-size: 16px;
```
Esta propiedad sirve para cambiar el tamaño de fuente, y el valor define el tamaño en píxeles.
```
color: black;
```
Esta propiedad sirve para cambiar el color del texto, y el valor define el color.
```
text-decoration: none/underline;
```
Esta propiedad se utiliza para cambiar el color del texto, y el valor define el color.
