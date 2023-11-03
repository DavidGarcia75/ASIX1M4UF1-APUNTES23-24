# ASIX1M4UF1-APUNTES23-24
<hr>
## GITHUB
<hr>
## MARKDOWN 
<hr>
## HTML
<hr>
## CSS
<hr>
-¿Que és?

El CSS  es un lenguaje de programación que se utiliza para dar estilo a los documentos HTML y XML. En otras palabras, el CSS se utiliza para definir cómo se deben mostrar los elementos HTML en una página web. Por ejemplo, el CSS se puede utilizar para cambiar el color de fondo de una página, el tamaño y el tipo de letra del texto, la posición de los elementos en la página.</p>

Para añadir estilos en CSS añadiremos la etiqueta style="">

Por ejemplo para poner un texto de color (rojo en este caso) sería de la siguiente forma:
<br>
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo1</title>
</head>
<body style="color: red;">
</body>
</html>
```

Para poner de color el fondo (azul en este caso) sera de la siguiente manera:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo2</title>
</head>
<body style="background-color:  rgb(0, 0, 255)">
    
</body>
</html>
```
Para poner una etiqueta CSS dentro de los elementos del html sería de la siguiente forma:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body {
            color: blueviolet;
        }
    </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo3</title>
</head>
<body>
    
</body>
</html>
```
Para poner estilo a elementos especificos utilizamos clases
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo4</title>
    <style>
        .textoAzul{
            color: blue
        }
    </style>
</head>
<body>
    <table>
<tbody>
<tr class="textoAzul">
    <td>Hola</td>
    <td>Hola</td>
    <td>Hola</td>
</tr>

</tbody>
    </table>

    
</body>
</html>
```
CUIDADO!! Las etiquetas de CSS van en orden descendente, es decir si pones una etiqueta
CSS para poner el texto en rojo, y luego pones una etiqueta para poner el texto en azul 
se aplicara la ultima etiqueta puesta.