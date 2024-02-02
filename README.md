# Curso Desarrollo Web

## Recursos Adicionales
Tabla Periodica HTML ([Enlace](https://lenguajehtml.com/html/introduccion/tabla-periodica-html5/))

Portafolio Bryan De la Cruz ([Enlace](https://lenguajehtml.com/html/introduccion/tabla-periodica-html5/))

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


## 5. Títulos en HTML
Los títulos h1 a h6 definen la jerarquía de la información. h1 es el título principal y h6 el menos relevante.
Facilita la comprensión y navegación del contenido. Los motores de búsqueda utilizan esta estructura para entender la relevancia de cada sección.
```html
<h1>Encabezado H1</h1>
<h2>Encabezado H2</h2>
<h3>Encabezado H3</h3>
```

## 6. Párrafos en HTML
Los elementos p se utilizan para estructurar el texto en párrafos, separando y organizando el contenido.

```html
<p>Este es un párrafo de texto.</p>
<p>Este es otro párrafo.</p>
```

## 7. Links en HTML
 El elemento a se utiliza para crear enlaces a otras páginas web, recursos o ubicaciones dentro de la misma página.

```html
<a href="https://www.google.com">Enlace a Ejemplo.com</a>
```
## 8. Manejo de Imágenes con HTML
El elemento <img> se utiliza para incrustar imágenes en una página HTML.

```html
<img src="imagen.jpg" alt="Descripción de la imagen">
```

## 9. Manejo de atributos
Los atributos como href, src, alt, width, height, entre otros, personalizan y controlan el comportamiento de los elementos HTML.

```html
<a href="https://www.ejemplo.com" target="_blank" title="Abrir en una nueva ventana">Enlace a Ejemplo.com</a>
<img src="imagen.jpg" alt="Descripción de la imagen" width="300" height="200">
```

## 10. Aplicar estilos CSS en HTML
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

## 11. Formato a texto en HTML
Concepto: HTML proporciona etiquetas para formatear texto, como negrita (strong), cursiva (em), subrayado (u), entre otras.

```html
<p>Texto <strong>resaltado</strong> con negrita.</p>
<p>Texto <em>enfasis</em> con cursiva.</p>
<p>Texto <u>subrayado</u>.</p>
```
## 12. Referencias de Caracteres en HTML
Las entidades HTML como &lt; representan caracteres especiales y símbolos que no pueden ser incluidos directamente en el código HTML.
Permite mostrar caracteres especiales sin interferir con la interpretación del navegador.

```html
<p>&copy; 2024 Mi Empresa</p>
<p>10 &lt; 20</p>
```