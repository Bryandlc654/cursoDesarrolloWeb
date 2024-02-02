# Curso Desarrollo Web

## Recursos Adicionales
Tabla Periodica HTML ([Enlace](https://lenguajehtml.com/html/introduccion/tabla-periodica-html5/))

Portafolio Bryan De la Cruz ([Enlace](https://bryandelacruz.nextboostperu.com/))



## 1. Mi primer página HTML
Una página HTML es la unidad básica de contenido en la web. Está compuesta por elementos HTML que se organizan jerárquicamente para estructurar y presentar información en un navegador web.


```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primera Página HTML</title>
</head>
<body>
    <h1>Hola, Mundo!</h1>
    <p>Esta es mi primera página HTML.</p>
</body>
</html>
```

## 1.1 Etiquetas en HTML
HTML tiene varias etiquetas que se utilizan para definir la estructura y contenido de una página web. Aquí tienes una lista de algunos de los tipos de etiquetas más comunes en HTML:

Etiquetas Básicas:
```html
<!DOCTYPE html>: Define el tipo de documento y la versión de HTML.
<html>: Define el inicio del documento HTML.
<head>: Contiene información sobre el documento, como metadatos y enlaces a archivos externos.
<title>: Define el título del documento que se muestra en la barra del navegador.
<body>: Contiene el contenido visible de la página.
Estructura de Texto:
<h1> a <h6>: Encabezados de diferentes niveles (1 es el más alto, 6 el más bajo).
<p>: Define un párrafo de texto.
<br>: Define un salto de línea.
<hr>: Crea una línea horizontal.
Listas:
<ul>: Define una lista no ordenada.
<ol>: Define una lista ordenada.
<li>: Define un elemento de lista.
Enlaces:
<a>: Define un enlace (hipervínculo).
Imágenes y Multimedia:
<img>: Inserta una imagen.
<audio>: Define contenido de audio.
<video>: Define contenido de video.
Formularios:
<form>: Define un formulario.
<input>: Define un campo de entrada en un formulario.
<textarea>: Define un área de texto en un formulario.
<button>: Define un botón en un formulario.
Tablas:
<table>: Define una tabla.
<thead>, <tbody>, <tfoot>: Define las partes de una tabla (encabezado, cuerpo, pie).
<tr>: Define una fila en una tabla.
<th>: Define una celda de encabezado en una tabla.
<td>: Define una celda de datos en una tabla.
Otros:
<div>: Define una división o contenedor genérico.
<span>: Define una sección en línea.
<strong>: Define texto importante y en negrita.
<em>: Define texto enfatizado y en cursiva.
<i>: Define texto en cursiva (no se recomienda, <em> es preferido).
```

## 1.2 Etiquetas Simples (Auto-cierre):
Estas etiquetas no tienen contenido y se cierran automáticamente.
```html
<img src="imagen.jpg" alt="Descripción de la imagen">
<br>
<hr>
<input type="text" placeholder="Nombre">
<meta charset="UTF-8">
```

## 1.3 Etiquetas de Apertura y Cierre:
Estas etiquetas tienen una apertura y un cierre explícitos, y pueden contener contenido entre ellas.
```html
<p>Este es un párrafo de texto.</p>
<a href="https://www.google.com">Enlace a Google</a>
<h1>Encabezado H1</h1>
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
</ul>
```

## 2. Formas de Ejecutar la Página Web HTML
Una página HTML puede ejecutarse localmente en un navegador o a través de un servidor web. El servidor local facilita el desarrollo al evitar problemas de política de origen al cargar recursos externos.

## 3. Meta UTF-8 en HTML
El meta tag meta charset="UTF-8" especifica la codificación de caracteres utilizada en la página, asegurando la correcta interpretación de caracteres especiales.
```html
<meta charset="UTF-8">
```

## 4. Generación Automática de HTML
Puedes generar la estructura inicial gracias a emmet, que viene incluido en vs code.
Método 1: Escribir html y seleccionar de la lista a HTML5.
Método 2: Escribir ! y presionar la tecla enter.

## 5. Comentarios en HTML
Enseña la importancia de comentarios en el código para hacerlo más legible y comprensible.
```html
<!-- Este es un comentario en HTML -->
<h1>Comentarios</h1>
```

## 6. Títulos en HTML
Los títulos h1 a h6 definen la jerarquía de la información. h1 es el título principal y h6 el menos relevante.
Facilita la comprensión y navegación del contenido. Los motores de búsqueda utilizan esta estructura para entender la relevancia de cada sección.
```html
<h1>Encabezado H1</h1>
<h2>Encabezado H2</h2>
<h3>Encabezado H3</h3>
```

## 7. Párrafos en HTML
Los elementos p se utilizan para estructurar el texto en párrafos, separando y organizando el contenido.

```html
<p>Este es un párrafo de texto.</p>
<p>Este es otro párrafo.</p>
```

## 8. Links en HTML
 El elemento a se utiliza para crear enlaces a otras páginas web, recursos o ubicaciones dentro de la misma página.

```html
<a href="https://www.google.com">Enlace a Ejemplo.com</a>
```
## 9. Manejo de Imágenes con HTML
El elemento <img> se utiliza para incrustar imágenes en una página HTML.

```html
<img src="imagen.jpg" alt="Descripción de la imagen">
```

## 10. Manejo de atributos
Los atributos como href, src, alt, width, height, entre otros, personalizan y controlan el comportamiento de los elementos HTML.

```html
<a href="https://www.ejemplo.com" target="_blank" title="Abrir en una nueva ventana">Enlace a Ejemplo.com</a>
<img src="imagen.jpg" alt="Descripción de la imagen" width="300" height="200">
```

## 11. Aplicar estilos CSS en HTML
CSS (Cascading Style Sheets) se utiliza para dar estilo y diseño a las páginas HTML. Permite controlar la apariencia de elementos, como colores, márgenes, fuentes, y más.

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Ejemplo de Estilos CSS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 20px;
        }

        h1 {
            color: #0077cc;
        }

        p {
            font-size: 16px;
            line-height: 1.5;
        }
    </style>
</head>
<body>
    <h1>Aplicando Estilos con CSS</h1>
    <p>Este es un párrafo con estilos aplicados mediante CSS.</p>
</body>
</html>
```

## 12. Formato a texto en HTML
Concepto: HTML proporciona etiquetas para formatear texto, como negrita (strong), cursiva (em), subrayado (u), entre otras.

```html
<p>Texto <strong>resaltado</strong> con negrita.</p>
<p>Texto <em>enfasis</em> con cursiva.</p>
<p>Texto <u>subrayado</u>.</p>
```
## 13. Referencias de Caracteres en HTML
Las entidades HTML como &lt; representan caracteres especiales y símbolos que no pueden ser incluidos directamente en el código HTML.
Permite mostrar caracteres especiales sin interferir con la interpretación del navegador.

```html
<p>&copy; 2024 Mi Empresa</p>
<p>10 &lt; 20</p>
```
## 14. Link para enviar un Email
El atributo mailto en un enlace <a> permite abrir el cliente de correo electrónico predeterminado con una dirección de correo predefinida.
Facilita a los usuarios la posibilidad de enviar correos electrónicos directamente desde la página web.

```html
<a href="mailto:correo@ejemplo.com">Envíanos un correo</a>
```

## 15. Manejo de Colores en CSS y HTML
CSS utiliza valores de color como nombres, códigos hexadecimales, o funciones RGB para definir colores.

```html
<style>
    body {
        background-color: #f0f0f0;
        color: #333;
    }

    h1 {
        color: rgb(255, 0, 0);
    }
</style>
```

## 16. Introducción a CSS
CSS (Cascading Style Sheets) es un lenguaje de diseño que controla la presentación y el estilo de un documento HTML.
Permite separar la estructura del contenido de su presentación, facilitando el mantenimiento y la consistencia del diseño.

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Introducción a CSS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 20px;
        }

        h1 {
            color: #0077cc;
        }
    </style>
</head>
<body>
    <h1>¡Bienvenido a la Introducción a CSS!</h1>
    <p>En este curso aprenderás a dar estilo a tus páginas web.</p>
</body>
</html>
```

## 17. Cascadeo en las hojas de estilo CSS
El principio del cascadeo en CSS determina cómo se aplican y priorizan los estilos cuando hay múltiples reglas que afectan al mismo elemento. Se basa en la especificidad y en el orden de las reglas.
Permite establecer un sistema de jerarquía para aplicar estilos de manera coherente y controlada.

```css
/* Regla más específica */
#miElemento {
    color: red;
}

/* Regla menos específica */
p {
    color: blue;
}

.text{
color: green;
}
```

## 18. Box Model en CSS
El modelo de caja en CSS describe cómo se representa visualmente cada elemento en la página, dividiéndolo en contenido, padding, borde y margen.
Facilita el control y diseño de la estructura visual de cada elemento.

```css
div {
    width: 200px;
    padding: 20px;
    border: 2px solid black;
    margin: 10px;
}
```

## 19.  Manejo de border, padding y margin en CSS
border establece el borde del elemento, padding añade espacio interno al contenido y margin establece el espacio externo alrededor del elemento.

```css
.box {
    border: 2px solid #333;
    padding: 10px;
    margin: 20px;
}
```

## 20.Estados y colores de los links en HTML y CSS
Los enlaces en HTML pueden tener diferentes estados como :link (sin visitar), :visited (visitado), :hover (sobre el enlace) y :active (activado).
Permite personalizar la apariencia de los enlaces en diferentes estados.

```css
a:link {
    color: blue;
}

a:hover {
    color: red;
}

a:visited {
    color: purple;
}
```

## 21. Links con imágenes en HTML
Los enlaces en HTML pueden contener imágenes usando la etiqueta img dentro de la etiqueta a.
Permite crear enlaces visuales que incluyen imágenes.

```html
<a href="https://www.ejemplo.com">
    <img src="imagen.jpg" alt="Descripción de la imagen">
</a>
```

## 22. Links como botones en HTML y CSS
Puedes estilizar los enlaces para que se vean y se comporten como botones mediante CSS. Esto incluye aplicar estilos de fondo, bordes y efectos de hover.

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Links como Botones</title>
    <style>
        .boton {
            display: inline-block;
            padding: 10px 20px;
            background-color: #3498db;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .boton:hover {
            background-color: #2980b9;
        }
    </style>
</head>
<body>
    <a href="#" class="boton">Botón</a>
</body>
</html>
```

## 23. Rutas relativas y absolutas en HTML
Las rutas relativas se definen desde la ubicación actual del archivo HTML, mientras que las rutas absolutas especifican la ruta completa desde la raíz del sitio.
Permite enlazar recursos como imágenes y archivos CSS de manera eficiente.

```html
<!-- Ruta relativa -->
<img src="imagenes/ejemplo.jpg" alt="Ejemplo de imagen">

<!-- Ruta absoluta -->
<link rel="stylesheet" href="https://ejemplo.com/estilos.css">
```

## 24. Tablas en HTML
Las tablas en HTML se crean utilizando las etiquetas table, tr para las filas y td para las celdas.
Permite organizar datos de manera tabular en una página web.

```html
<table border="1">
    <tr>
        <td>Columna 1</td>
        <td>Columna 2</td>
    </tr>
    <tr>
        <td>Dato 1</td>
        <td>Dato 2</td>
    </tr>
</table>
```

## 24.1 Partes de una Tabla en HTML
1. Etiqueta table
La etiqueta table envuelve toda la estructura de la tabla
```html
<table>
    <!-- Contenido de la tabla va aquí -->
</table>
```

2. Etiqueta thead
La sección de encabezado de la tabla, que generalmente contiene las etiquetas th.
```html
<thead>
    <tr>
        <th>Encabezado 1</th>
        <th>Encabezado 2</th>
    </tr>
</thead>
```

3. Etiqueta tbody
La sección del cuerpo de la tabla, donde se encuentran las filas y celdas principales.
```html
<tbody>
    <tr>
        <td>Dato 1</td>
        <td>Dato 2</td>
    </tr>
    <!-- Más filas pueden seguir -->
</tbody>
```

4. Etiqueta tfoot
La sección del pie de la tabla, que generalmente contiene resúmenes o totales.
```html
<tfoot>
    <tr>
        <td>Total:</td>
        <td>$100</td>
    </tr>
</tfoot>
```

5.  Etiqueta tr
Define una fila dentro de la tabla.
```html
<tr>
    <td>Dato A</td>
    <td>Dato B</td>
</tr>
```

6. Etiqueta th
Define una celda de encabezado dentro de la tabla.
```html
<tr>
    <th>Encabezado A</th>
    <th>Encabezado B</th>
</tr>
```

6. Etiqueta td
Define una celda de datos dentro de la tabla.
```html
<tr>
    <td>Dato 1</td>
    <td>Dato 2</td>
</tr>
```


## 25. Tablas en HTML con CSS
Se pueden aplicar estilos CSS a las tablas para personalizar la apariencia, ajustar márgenes y espaciados.
Mejora la presentación visual de las tablas en la página web.

```css
<style>
    table {
        width: 100%;
        border-collapse: collapse;
    }

    th, td {
        border: 1px solid #ddd;
        padding: 8px;
        text-align: left;
    }

    th {
        background-color: #f2f2f2;
    }
</style>
```

## 26. Atributos colspan y rowspan en tablas HTML
colspan define cuántas columnas ocupa una celda, y rowspan define cuántas filas ocupa una celda.
Permite combinar celdas para estructurar mejor la información en tablas.

```html
<table border="1">
    <tr>
        <td colspan="2">Celda que ocupa dos columnas</td>
    </tr>
    <tr>
        <td>Fila 2 - Columna 1</td>
        <td>Fila 2 - Columna 2</td>
    </tr>
</table>
```
