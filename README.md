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
### Encabezados
```html
  <h1>el más grande</h1>
```
<h1> el más grande
<h2> menos grande
<h3> normal
<h4> medio
<h5> pequeño
<h6> más pequeño
