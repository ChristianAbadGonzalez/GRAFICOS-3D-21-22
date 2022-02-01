Vamos a comenzar a realizar la práctica P0 de la asignatura en cuestión.

<!-- 

EJERCICIOS DE LA PARTE DE HTML.
*******************************

DECLARACIÓN DE BLOQUES DE HTML
******************************

La Declaración <!DOCTYPE>
*************************

La <!DOCTYPE> declaración representa el tipo de documento y ayuda a los navegadores a mostrar correctamente las páginas web.

Solo debe aparecer una vez, en la parte superior de la página (antes de cualquier etiqueta HTML).

La <!DOCTYPE> declaración no distingue entre mayúsculas y minúsculas.

La <!DOCTYPE> declaración que define que este es un documento para HTML5 es:

<!DOCTYPE html>
***************************************************************************************************************************************

El <html> elemento es el elemento raíz de una página HTML.
***************************************************************************************************************************************

El <head> elemento contiene metainformación sobre la página HTML.
***************************************************************************************************************************************

El <title> elemento especifica un título para la página HTML (que se muestra en la barra de título del navegador o en la pestaña de la página)
***************************************************************************************************************************************

El <body> elemento define el cuerpo del documento y es un contenedor de todos los contenidos visibles, como encabezados, párrafos, imágenes, hipervínculos, tablas, listas, etc.
***************************************************************************************************************************************

Encabezados HTML
****************

Los encabezados HTML se definen con las etiquetas <h1> a <h6>

El <h1> elemento define un encabezado grande

<h1> define el encabezado más importante. <h6> define el encabezado menos importante:

EJEMPLO:

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
***************************************************************************************************************************************

Párrafos en HTML
****************

Los párrafos HTML se definen con la etiqueta <p>

El <p> elemento define un párrafo.

EJEMPLO:
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
***************************************************************************************************************************************

Enlaces HTML
************

Los enlaces HTML se definen con la etiqueta <a>

El destino del enlace se especifica en el href atributo. 

Los atributos se utilizan para proporcionar información adicional sobre los elementos HTML.

EJEMPLO:
<a href="https://www.w3schools.com">This is a link</a>
***************************************************************************************************************************************

Imágenes HTML
*************

Las imágenes HTML se definen con la <img>etiqueta.

El archivo de origen (src), el texto alternativo (alt), widthy height se proporcionan como atributos:

EJEMPLO:
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
***************************************************************************************************************************************

-->

<!--

***************************************************************************************************************************************
-->

<!-- 

Usando CSS

CSS se puede agregar a documentos HTML de 3 maneras:

CSS en Línea
************

En línea : mediante el uso del styleatributo dentro de los elementos HTML

Se utiliza un CSS en línea para aplicar un estilo único a un solo elemento HTML.

Un CSS en línea usa el style atributo de un elemento HTML.

El siguiente ejemplo establece el color del texto del <h1> elemento en azul y el color del texto del <p> elemento en rojo:

<h1 style="color:blue;"> A Blue Heading</h1>

<p style="color:red;"> A red paragraph.</p>

***************************************************************************************************************************************

CSS Interno
***********

Se utiliza un CSS interno para definir un estilo para una sola página HTML.

Un CSS interno se define en la <head> sección de una página HTML, dentro de un <style> elemento.

El siguiente ejemplo establece el color del texto de TODOS los <h1> elementos (en esa página) en azul y el color del texto de TODOS los <p> elementos en rojo. Además, la página se mostrará con un color de fondo "powderblue": 

Interno - mediante el uso de un <style> elemento en la <head> sección

<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
***************************************************************************************************************************************

CSS Externo
***********

Se utiliza una hoja de estilo externa para definir el estilo de muchas páginas HTML.

Para usar una hoja de estilo externa, agregue un enlace en la <head>sección de cada página HTML:

Externo : mediante el uso de un <link> elemento para vincular a un archivo CSS externo

<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
***************************************************************************************************************************************

La forma más común de agregar CSS es mantener los estilos en archivos CSS externos. Sin embargo, en este tutorial usaremos estilos en línea e internos, porque esto es más fácil de demostrar y más fácil para que usted mismo lo pruebe.


La hoja de estilo externa se puede escribir en cualquier editor de texto. El archivo no debe contener ningún código HTML y debe guardarse con una extensión .css.

Así es como se ve el archivo "styles.css":

styles.css

body {
  background-color: powderblue;
}

h1 {
  color: blue;
}

p {
  color: red;
}

***************************************************************************************************************************************

Colores, fuentes y tamaños CSS
******************************

Aquí, demostraremos algunas propiedades CSS de uso común. Aprenderás más sobre ellos más adelante.

La propiedad CSS color define el color del texto que se utilizará.

La propiedad CSS font-family define la fuente que se utilizará.

La propiedad CSS font-size define el tamaño del texto que se utilizará.

Ejemplo HTML con CSS Interno:
*****************************

<!DOCTYPE html>
<html>

<head>

<style>

h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;
}

p {
  color: red;
  font-family: courier;
  font-size: 160%;
}

</style>

</head>

<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>

</html>

***************************************************************************************************************************************

Borde CSS
*********

La propiedad CSS border define un borde alrededor de un elemento HTML.

Sugerencia: puede definir un borde para casi todos los elementos HTML.

Ejemplo

Uso de la propiedad de borde CSS:

p {
  border: 2px solid powderblue;
}
***************************************************************************************************************************************

Relleno CSS
***********

La propiedad CSS paddingdefine un relleno (espacio) entre el texto y el borde.

Ejemplo

Uso de borde CSS y propiedades de relleno:

p {
  border: 2px solid powderblue;
  padding: 30px;
}
***************************************************************************************************************************************

Margen CSS
**********

La propiedad CSS margin define un margen (espacio) fuera del borde.

Ejemplo

Uso de las propiedades de borde y margen CSS:

p {
  border: 2px solid powderblue;
  margin: 50px;
}
***************************************************************************************************************************************

Enlace a CSS Externo

Las hojas de estilo externas se pueden referenciar con una URL completa o con una ruta relativa a la página web actual.

Ejemplo

Este ejemplo utiliza una URL completa para vincular a una hoja de estilo:

<link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">
***************************************************************************************************************************************
 -->
 
<!-- 
***************************************************************************************************************************************
 -->