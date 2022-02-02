Vamos a comenzar a realizar la práctica P0 de la asignatura en cuestión.

# HTML 

## EJERCICIOS DE LA PARTE DE HTML.  

### DECLARACIÓN DE BLOQUES DE HTML  
    La Declaración <!DOCTYPE>.  
    
    La <!DOCTYPE> declaración representa el tipo de documento y ayuda a los navegadores a mostrar correctamente las páginas web.  
    
    Solo debe aparecer una vez, en la parte superior de la página (antes de cualquier etiqueta HTML).  
    
    La <!DOCTYPE> declaración no distingue entre mayúsculas y minúsculas.  
    
    La <!DOCTYPE> declaración que define que este es un documento para HTML5 es:

```
<!DOCTYPE html>
El <html> elemento es el elemento raíz de una página HTML.

El <head> elemento contiene metainformación sobre la página HTML.

El <title> elemento especifica un título para la página HTML (que se muestra en la barra de título del navegador o en la pestaña de la página)

El <body> elemento define el cuerpo del documento y es un contenedor de todos los contenidos visibles, como encabezados, párrafos, imágenes, hipervínculos, tablas, listas, etc.

```

## Encabezados HTML

    Los encabezados HTML se definen con las etiquetas  
    <h1></h1> a <h6></h6>.  
    El <h1></h1> elemento define un encabezado más importante.  
    El <h6></h6> elemento define un encabezado menos importante.

### EJEMPLO:  
      <h1>This is heading 1</h1>  
      <h2>This is heading 2</h2>  
      <h3>This is heading 3</h3>  

## Párrafos en HTML  
      Los párrafos HTML se definen con la etiqueta <p></p>  
      El <p></p> elemento define un párrafo.

### EJEMPLO: 
      <p>This is a paragraph.</p>  
      <p>This is another paragraph.</p>

## Enlaces HTML  
      Los enlaces HTML se definen con la etiqueta <a></a>  
      El destino del enlace se especifica en el href atributo.  
      Los atributos se utilizan para proporcionar información  
      adicional sobre los elementos HTML.

### EJEMPLO:  
      <a href="https://www.w3schools.com">This is a link</a>

## Imágenes HTML  
      Las imágenes HTML se definen con la <img>etiqueta.  
      El archivo de origen (src), el texto alternativo (alt)  
      widthy height se proporcionan como atributos:

### EJEMPLO:  
      <img src="w3schools.jpg" alt="W3Schools.com" width="104"  height="142">
***  

# CSS 

Usando CSS --> CSS se puede agregar a documentos HTML de 3 maneras:  
*** 
    
## CSS en Línea.  
En línea : mediante el uso del styleatributo dentro de los elementos HTML.  
        
Se utiliza un CSS en línea para aplicar un estilo único a un solo elemento HTML.  
        
Un CSS en línea usa el style atributo de un elemento HTML.  
***
## CSS Interno:  
Se utiliza un CSS interno para definir un estilo para una sola página HTML.  

Un CSS interno se define en la "head"sección de una página HTML, dentro de un "style" del elemento.
  
El siguiente ejemplo establece el color del texto de TODOS los encabezados "h1" hasta "h6" elementos ubicados en esa página en azul.  

El color del texto de TODOS los parrafos "p" elementos en color rojo.  

Además, la página se mostrará con un color de fondo "powderblue".  

Interno - mediante el uso de un: "style" elemento en la "head" sección.  
***     
## CSS Externo:  
Se utiliza una hoja de estilo externa para definir el  estilo de muchas páginas HTML.  
Para usar una hoja de estilo externa, agregue un enlace en la "head" sección de cada página HTML.  
        
Externo : mediante el uso de un <link> elemento para vincular a un archivo CSS externo.
****
# EJEMPLO CSS EN LÍNEA:  
    El siguiente ejemplo establece el color del texto del <h1></h1> elemento en azul y el color del texto del <p></p> elemento en rojo:  

    <h1 style="color:blue;"> A Blue Heading</h1>  
    <p style="color:red;"> A red paragraph.</p>


# EJEMPLO CSS INTERNO:  
    !-- <!DOCTYPE html>
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

# EJEMPLO CSS EXTERNO:  
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
***
La forma más común de agregar CSS es mantener los estilos en archivos CSS externos. Sin embargo, en este tutorial usaremos estilos en línea e internos, porque esto es más fácil de demostrar y más fácil para que usted mismo lo pruebe.  

La hoja de estilo externa se puede escribir en cualquier editor de texto. El archivo no debe contener ningún código HTML y debe guardarse con una extensión .css.
***
# Archivo "styles.css":  
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
 ***

# Colores, fuentes y tamaños CSS  
Aquí, demostraremos algunas propiedades CSS de uso común. Aprenderás más sobre ellos más adelante.  
    
La propiedad CSS color define el color del texto que se utilizará.  
    
La propiedad CSS font-family define la fuente que se utilizará.  
    
La propiedad CSS font-size define el tamaño del texto que se utilizará.
***
# Ejemplo HTML con CSS Interno:  
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
***

# Borde CSS:  
La propiedad CSS border define un borde alrededor de un elemento HTML.  
    
Sugerencia: puede definir un borde para casi todos los elementos HTML.

# Ejemplo:  
    Uso de la propiedad de borde CSS:  
    p {  
      border: 2px solid powderblue;  
    }
***

# Relleno CSS:  
La propiedad CSS paddingdefine un relleno (espacio) entre el texto y el borde.

# Ejemplo:  
    Uso de borde CSS y propiedades de relleno:  
    p {  
      border: 2px solid powderblue;  
      padding: 30px;  
    }
***

# Margen CSS:  
La propiedad CSS margin define un margen (espacio) fuera del borde.

# Ejemplo  
    Uso de las propiedades de borde y margen CSS:  
    
    p {  
        border: 2px solid powderblue;  
        margin: 50px;  
    }

# Enlace a CSS Externo  
Las hojas de estilo externas se pueden referenciar con una URL completa o con una ruta relativa a la página web actual.

# Ejemplo:  
    Este ejemplo utiliza una URL completa para vincular a una hoja de estilo:  
    
    <link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">


# JAVASCRIPT  

JavaScript hace que las páginas HTML sean más dinámicas e interactivas.


# EJEMPLO JAVASCRIPT  
    <!DOCTYPE html>  
    <html>  
    <body>  
    <h1> My First JavaScript </h1>  
    
    <button type="button" onclick="document.getElementById('demo').innerHTML = Date()">  
    
    Click me to display Date and Time.</button>  
    
    <p id="demo"></p>  
    
    </body>  
    
    </html>  
    
La etiqueta HTML "script" se utiliza para definir un script del lado del cliente (JavaScript).

El elemento script contiene sentencias de script o apunta a un archivo de script externo a través del "src" atributo.

Los usos comunes de JavaScript son la manipulación de imágenes, la validación de formularios y los cambios dinámicos de contenido.

Para seleccionar un elemento HTML, JavaScript suele utilizar el document.getElementById() método.

Este ejemplo de JavaScript escribe "¡Hola, JavaScript!" en un elemento HTML con id="demo":  

## EJEMPLO:  
    <script>  
      document.getElementById("demo").innerHTML = "Hello JavaScript!";  
    </script>

## EJEMPLO JAVASCRIPT 1
JavaScript puede cambiar el contenido:  
    
    document.getElementById("demo").innerHTML = "Hello JavaScript!";

## EJEMPLO JAVASCRIPT 2
JavaScript puede cambiar estilos:  

    document.getElementById("demo").style.fontSize = "25px";  
    document.getElementById("demo").style.color = "red";  
    document.getElementById("demo").style.backgroundColor = "yellow";

## EJEMPLO JAVASCRIPT 3
JavaScript puede cambiar atributos:  

      document.getElementById("image").src = "picture.gif";

***
## ETIQUETA DE HTML "noscript" EN JAVASCRIPT:  
La etiqueta "noscript" en HTML define un contenido alternativo que se mostrará a los usuarios que tienen scripts deshabilitados en su navegador o tienen un navegador que no admite scripts:  

## EJEMPLO DE LA ETIQUETA "noscript"  
    <script>  
      document.getElementById("demo").innerHTML = "Hello JavaScript!";  
    </script>  
    
    <noscript>  
      Sorry, your browser does not support JavaScript!  
    </noscript>
***
## ETIQUETA "SCRIPT":  
    En HTML, el código JavaScript se inserta entre las etiquetas <script> y </script>

### EJEMPLO:  
    <script>  
      document.getElementById("demo").innerHTML = "My Frist JavaScript!";  
    </script>
***
### FUNCIONES Y EVENTOS DE JAVASCRIPT
Un JavaScript functiones un bloque de código JavaScript, que se puede ejecutar cuando se "llama".

Por ejemplo, se puede llamar a una función cuando ocurre un evento , como cuando el usuario hace clic en un botón.
***
### JavaScript en "HEAD" o "BODY"
Puede colocar cualquier número de secuencias de comandos en un documento HTML.

Los scripts se pueden colocar en el "body",  
o en la "head" sección de una página HTML, o en ambos.
***

### JavaScript en "HEAD":  

"function" En este ejemplo, se coloca un JavaScript en la "head" sección de una página HTML.

La función se invoca/llama cuando se hace clic en un botón:  

### EJEMPLO "HEAD":  
    <!DOCTYPE html>  
    <html>  
    <head>  
    <script>  
    
      function myFunction() {  
        document.getElementById("demo").innerHTML = "Paragraph changed.";  
      }  
    
    </script>  
    </head>  
    <body>  
      <h2>Demo JavaScript in Head</h2>  
      
      <p id="demo">A Paragraph</p>  
      <button type="button" onclick="myFunction()">Try it</button>  
      </body>  
      </html>
***

### JavaScript en "BODY":  
functionEn este ejemplo, se coloca un JavaScript en la "body" sección de una página HTML.  

La función se invoca (llama) cuando se hace clic en un botón:

### EJEMPLO DE "BODY":  
    <!DOCTYPE html>  
    <html>  
    <body>  
    
        <h2>Demo JavaScript in Body</h2>  
        <p id="demo">A Paragraph</p>  
        <button type="button" onclick="myFunction()">Try it</button>  
      <script>  
        function myFunction() {  
          document.getElementById("demo").innerHTML = "Paragraph changed.";  
        }  
      </script>  
    </body>  
    </html>
***
### JAVASCRIPT EXTERNO:  
Los scripts también se pueden colocar en archivos externos:  

#### EJEMPLO:  
    function myFunction() {  
      document.getElementById("demo").innerHTML = "Paragraph changed.";  
    }

Los scripts externos son prácticos cuando se usa el mismo código en muchas páginas web diferentes.

Los archivos JavaScript tienen la extensión de archivo .js .

Para usar una secuencia de comandos externa, coloque el nombre del archivo de secuencia de comandos en el srcatributo (fuente) de una "script" etiqueta:  

#### EJEMPLO:  
      <script src="myScript.js"></script>

Puede colocar una referencia de secuencia de comandos externa en "head" o "body" como desee.

El script se comportará como si estuviera ubicado exactamente donde se encuentra la "script" etiqueta.

# NOTA:  
    Los scripts externos no pueden contener <script> etiquetas.
***
## VENTAJAS DE TENER UN JAVASCRIPT EXTERNO:  
Colocar scripts en archivos externos tiene algunas ventajas:

1. Separa HTML y código.  

2. Hace que HTML y JavaScript sean más fáciles de leer y mantener  

3. Los archivos JavaScript almacenados en caché pueden acelerar la carga de la página.  

Para agregar varios archivos de script a una página, use varias etiquetas de script.

### EJEMPLO:  
    <script src="myScript1.js"></script>  
    <script src="myScript2.js"></script>

***
## REFERENCIAS EXTERNAS EN JAVASCRIPT:  
Se puede hacer referencia a un script externo de 3 maneras diferentes:

1. Con una URL completa (una dirección web completa).  

2. Con una ruta de archivo (como /js/).  

3. Sin ningún camino.  

### EJEMPLO 1:   
    <script src="https://www.w3schools.com/js/myScript.js"></script>
    
Este ejemplo usa una URL completa para vincular a myScript.js

### EJEMPLO 2:  
    <script src="/js/myScript.js"></script>

Este ejemplo utiliza una ruta de archivo para vincular a myScript.js.

### EJEMPLO 3:  
      <script src="myScript.js"></script>

Este ejemplo no usa una ruta para vincular a myScript.js:
***
## VARIABLES EN JAVASCRIPT:  
Las variables son contenedores para almacenar datos (almacenar valores de datos).  

En este ejemplo, x, y y z, son variables declaradas con la  palabra clave "var":  

### EJEMPLOS:  
    var x = 5;  
    var y = 6;  
    var z = x + y;  
***  
En este ejemplo, x, y y z, son variables declaradas con la palabra clave "let":  

    let x = 5;  
    let y = 6;  
    let z = x + y;
***  
En este ejemplo, x, y y z, son variables no declaradas:  
    
    x = 5;  
    y = 6;  
    z = x + y;
***  
## ¿CUÁNDO USAR "VAR" EN JAVASCRIPT?  
Declare siempre las variables de JavaScript con var, let o const.  

La palabra clave "var" se usa en todo el código JavaScript desde 1995 hasta 2015.  

Las palabras clave let y const se agregaron a JavaScript en 2015.  

Si desea que su código se ejecute en un navegador anterior, debe usar var.  
***
## ¿CUÁNDO USAR "CONST" EN JAVASCRIPT?  
Si quieres una regla general: declara siempre las variables con const.

Si cree que el valor de la variable puede cambiar, use let.

En este ejemplo, price1, price2y total, son variables:  
### EJEMPLO:  
    const price1 = 5;  
    const price2 = 6;  
    let total = price1 + price2;  
Las dos variables price1y price2 se declaran con la constpalabra clave.

Estos son valores constantes y no se pueden cambiar.

La variable totalse declara con la letpalabra clave.

Este es un valor que se puede cambiar.  
***  
## ¡¡ALGEBRA EN JAVASCRIPT!!  
Al igual que en álgebra, las variables tienen valores:  
    
    let x = 5;  
    let y = 6;  
Al igual que en álgebra, las variables se usan en expresiones:  

    let z = x + y;  

## ¡NOTA!: Las variables son contenedores para almacenar valores.  
***  
## IDENTIFICADORES EN JAVASCRIPT.  
Todas las variables de JavaScript deben identificarse con nombres únicos .

Estos nombres únicos se denominan identificadores .

Los identificadores pueden ser nombres cortos (como x e y) o nombres más descriptivos (edad, suma, volumen total).

Las reglas generales para construir nombres para variables (identificadores únicos) son:

1. Los nombres pueden contener letras, dígitos, guiones bajos y signos de dólar.  
2. Los nombres deben comenzar con una letra.  
3. Los nombres también pueden comenzar con $ y _ (pero no lo usaremos en este tutorial).  
4. Los nombres distinguen entre mayúsculas y minúsculas (y e Y son variables diferentes).  
5. Las palabras reservadas (como las palabras clave de JavaScript) no se pueden usar como nombres.  

## ¡NOTA!: Los identificadores de JavaScript distinguen entre mayúsculas y minúsculas.  
***  
## OPERADOR ASIGNACIÓN "=":  
En JavaScript, el signo igual ( =) es un operador de "asignación", no un operador "igual a".

Esto es diferente del álgebra. Lo siguiente no tiene sentido en álgebra.  

    x = x + 5  

En JavaScript, sin embargo, tiene mucho sentido: asigna el valor de x + 5 a x.  

(Calcula el valor de x + 5 y pone el resultado en x. El valor de x se incrementa en 5).  

## ¡NOTA!: El operador "igual a" se escribe como "==" en JavaScript.  

***  
## TIPOS DE DATOS EN JAVASCRIPT.  
Las variables de JavaScript pueden contener números como 100 y valores de texto como "John Doe".  

En programación, los valores de texto se denominan cadenas de texto.  

JavaScript puede manejar muchos tipos de datos, pero por ahora, solo piense en números y cadenas.  

Las cadenas se escriben entre comillas simples o dobles. Los números se escriben sin comillas.  

Si pone un número entre comillas, se tratará como una cadena de texto.  

    const pi = 3.14;  
    let person = "John Doe";  
    let answer = 'Yes I am!';  
***  
## DECLARAR UNA VARIABLE EN JAVASCRIPT  

Crear una variable en JavaScript se llama "declarar" una variable.  

Declaras una variable de JavaScript con varo la letpalabra clave:  

    var carName;  
    o  
    let carName;  

Después de la declaración, la variable no tiene valor (técnicamente lo es undefined).  

Para asignar un valor a la variable, utilice el signo igual:  

    carName = "Volvo";  
También puede asignar un valor a la variable cuando la declara:  

    let carName = "Volvo";  

En el siguiente ejemplo, creamos una variable llamada carNamey le asignamos el valor "Volvo".  

Luego, "damos salida" al valor dentro de un párrafo HTML con id="demo":  

    <p id="demo"></p>  
    
    <script>  
      
      let carName = "Volvo";  
      document.getElementById("demo").innerHTML = carName;  
    
    </script>  

### ¡NOTA!: Es una buena práctica de programación declarar todas las variables al comienzo de un script.

***
## UNA DECLARACIÓN -- MUCHAS VARIABLES  

Puede declarar muchas variables en una declaración.  

Comience la declaración con vary separe las variables con comas:  

    let person = "John Doe", carName = "Volvo", price = 200;

Una declaración puede abarcar varias líneas:  

    let person = "John Doe",  
    carName = "Volvo",  
    price = 200;  

***
## VALOR INDEFINIDO -- (UNDEFINED)  
En los programas de computadora, las variables a menudo se declaran sin valor. El valor puede ser algo que debe calcularse o algo que se proporcionará más adelante, como una entrada del usuario.  

Una variable declarada sin valor tendrá el valor undefined.  

La variable carName tendrá el valor undefineddespués de la ejecución de esta declaración:  

    let carName;  
***
## REDECLARACIÓN DE VARIABLES EN JAVASCRIPT  

Si vuelve a declarar una variable de JavaScript declarada con "var", no perderá su valor.  

La variable carNameseguirá teniendo el valor "Volvo" después de la ejecución de estas sentencias:  

    var carName = "Volvo";  
    var carName;  

### ¡NOTA! No puede volver a declarar una variable declarada con let o const.  

    ¡¡ESTO NO FUNCIONARA!!  

      let carName = "Volvo";  
      let carName;  
***
## ARITMETICA EN JAVASCRIPT  
Al igual que con el álgebra, puedes hacer operaciones aritméticas con variables de JavaScript,  
usando operadores como = y +:  

    let x = 5 + 2 + 3;  

    let x = "John" + " " + "Doe";  --> Resultado: John Doe.

    let x = "5" + 2 + 3;  --> Resultado: 55.  

### ¡NOTA! Si se pone un número o nombre entre comillas, el resto de los números o nombres se tratarán como cadenas y se concatenarán.  

***  
## SIMBOLO "$" EN JAVASCRIPT  

Dado que JavaScript trata un signo de dólar como una letra,  
los identificadores que contienen $ son nombres de variables válidos:  

    let $ = "Hello World";  
    
    let $$$ = 2;  
    
    let $myMoney = 5;  

Usar el signo de dólar no es muy común en JavaScript,  
pero los programadores profesionales a menudo lo usan como un alias  
para la función principal en una biblioteca de JavaScript.

En la biblioteca JavaScript jQuery, por ejemplo,  
la función principal "DOLAR" se usa para seleccionar elementos HTML.  
En jQuery "DOLAR("p")"; significa "seleccionar todos los elementos p".  
***  
## GUIÓN BAJO "_" EN JAVASCRIPT

Dado que JavaScript trata el guión bajo como una letra, los identificadores que contienen "_" son nombres de variables válidos:  

    let _lastName = "Johnson";  
    
    let _x = 2;  
    
    let _100 = 5;  

Usar el guión bajo no es muy común en JavaScript,  
pero una convención entre los programadores profesionales  
es usarlo como un alias para las variables "privadas (ocultas)".

