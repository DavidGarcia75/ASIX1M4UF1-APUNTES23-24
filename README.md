# ASIX1M4UF1-APUNTES23-24
<hr>
## GITHUB
<hr>
## MARKDOWN 
-¿Que és?

Markdown es un lenguaje de marcado que pretende ofrecer la máxima facilidad de lectura al usuario. Sus comandos de formateado no son abstractos, sino cercanos al significado real. 
<br>
<h3>Negritas y Cursivas</h3>
Crear negritas y cursivas con Markdown es particularmente fácil, ya que solo son necesarios los asteriscos. Para poner una palabra o grupo de palabras en cursiva, inserta un asterisco antes y después de ellas. Para la negrita, utiliza dos. Si deseas remarcar un área de texto en negrita y cursiva, pon tres asteriscos. Como alternativa, también puedes utilizar guiones bajos.

```
*Texto en cursiva*
_Texto en cursiva_

**Texto en negrita**
__Texto en negrita__

***Texto en cursiva y negrita***
___Texto en cursiva y negrita___
```
<h3>Tachado</h3>

Para representar un texto tachado en Markdown, escribe dos virgulillas seguidas; después, escribe el texto correspondiente y ciérralo con otras dos virgulillas.
```
~~Este texto está tachado.~~ Pero este no.
```
<h3>Título</h3>
Para crear un título en Markdown, se utiliza de forma predeterminada una almohadilla, que se pone delante del texto, separada por un espacio en blanco. Para crear subtítulos y, por lo tanto, en letra más pequeña, se insertan más almohadillas. De esta manera, se pueden crear hasta seis niveles de títulos, como en HTML.
<br>

```
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
```
<h3>Comillas</h3>
Para marcar un fragmento de texto como una cita en Markdown, puedes crear las llamadas citas en bloque, utilizando el signo de mayor que (>).
<br>

Tienes dos opciones: marcar cada línea individual con este carácter o insertar únicamente uno al principio del párrafo de la cita sangrada y marcar el fin de la cita introduciendo una línea en blanco. La cita en bloque, a su vez, puede ser formateada con otros elementos.

```
>Este es un **fragmento con comillas**.
>El fragmento continúa aquí.

>Este es otro **fragmento con comillas**.
Este fragmento continúa en la siguiente línea.

Esta línea ya no está sangrada.
```
<h3>Listas</h3>
Para crear una lista no ordenada en Markdown, puedes utilizar el signo de más, un guion o un asterisco. Con las tres opciones obtendrás el mismo resultado.

```
- Elemento de la lista 1
- Elemento de la lista 2
- Elemento de la lista 3
```
Si lo quieres introducir en una lista ordenada lo deberás hacer de la siguiente forma:

```
1. Elemento de la lista 1
2. Elemento de la lista 2
3. Elemento de la lista 3
```
Asimismo, Markdown te da la opción de crear listas de verificación, que vienen con casillas que pueden activarse haciendo clic sobre ellas. Si quieres, puedes marcar directamente las casillas al crear la lista. Para ello, utiliza corchetes y una X.

```
[ ] A
[x] B
[ ] C

```
<h3>Código</h3>

```
Esto es `código`.
```
<h3>Imagenes e Hipervínculos</h3>

```
A continuación se muestra un [Link](https://ejemplo.com/ "Título opcional del enlace").
```
Otra forma de insertar puede ser esta:

```
<https://ejemplo.com>
`https://ejemplo.com`
```
<h3>Tablas</h3>
Markdown permite dibujar tablas mediante plecas (|). Cada celda está separada por uno de estos caracteres. Para crear encabezados que se distingan visualmente del resto del contenido, se subrayan las celdas correspondientes con guiones.

```
|Columna 1|Columna 2|
|--------|--------|
|    A    |    B    |
|    C    |    D    |
```
<hr>
<h2>HTML</h2>
## HTML
-¿Que és?

El Lenguaje de Marcado de Hipertexto (HTML) es el código que se utiliza para estructurar y desplegar una página web y sus contenidos. Por ejemplo, sus contenidos podrían ser párrafos, una lista con viñetas, o imágenes y tablas de datos. Como lo sugiere el título, este artículo te dará una comprensión básica de HTML y cúal es su función.

Etiquetas HTML: 
<br>
La etiqueta `<p>` sirve para introducir un parrafo al documento HTML
<br>
<br>
Las partes principales del elemento son:

La etiqueta de apertura: consiste en el nombre del elemento (en este caso, p), encerrado por paréntesis angulares (< >) de apertura y cierre. Establece dónde comienza o empieza a tener efecto el elemento
<br>
<br>
La etiqueta de cierre: es igual que la etiqueta de apertura, excepto que incluye una barra de cierre (/) antes del nombre de la etiqueta. Establece dónde termina el elemento 
 <br>
 <br>
 La etiqueta `strong` sirve para destacar el texto deseado en negrita
 <br>
 <br>
 Sintaxis:
 <br>
 `<p>Mi gato es <strong>muy</strong> gruñon.</p>`
 <br>
 <br>
 Ejemplo:
 p>Mi gato es <strong>muy</strong> gruñon.</p>
 <hr>               
    
La etiqueta `<img>`sirve para insertar una imagen dentro del html
<br>
<br>
Sintaxis:
`<img src="images/firefox-icon.png" alt="Mi imagen de prueba" />`
<br>
<br>
La primera parte se especificara la ruta de la foto (donde tienes guardada esa foto") Y la segunda sección hace referencia al texto que quieres que vaya asociado a la imagen
<br>
<h3>Anatomia de un documento HTML:</h3>
<br>

```
<!doctype html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Mi pagina de prueba</title>
  </head>
  <body>
    <img src="images/firefox-icon.png" alt="Mi imagen de prueba" />
  </body>
</html>
```
El elemento `head`: Este elemento actúa como un contenedor de todo aquello que quieres incluir en la página HTML que no es contenido visible por los visitantes de la página. Incluye cosas como palabras clave (keywords), una descripción de la página que quieres que aparezca en resultados de búsquedas, código CSS para dar estilo al contenido, declaraciones del juego de caracteres, etc.
<br>
<br>
<hr>

El elemento `title`: Establece el título de tu página, que es el título que aparece en la pestaña o en la barra de título del navegador cuando la página es cargada, y se usa para describir la página cuando es añadida a los marcadores o como favorita.
<br>
<br>
<hr>

El elemento `body`: Encierra todo el contenido que deseas mostrar a los usuarios web que visiten tu página, ya sea texto, imágenes, videos, juegos, pistas de audio reproducibles, y demás.


<h3>Encabezados</h3>
Los encabezadospermiten especificar que ciertas partes del contenido son encabezados, o subencabezados del contenido. De la misma forma que un libro tiene un título principal, y que a su vez puede tener títulos por cada capítulo individual, y subtítulos dentro de ellos, un documento HTML puede tenerlos también. HTML posee seis niveles de encabezados, 

`<h1>` hasta `<h6>`
<br>

De más grande a mas pequeño en funcion del numero que se introduzca con la "h"

Ejemplo:
```
<h1>Mi título principal</h1>
<h2>Mi título de nivel superior</h2>
<h3>Mi subtítulo</h3>
<h4>Mi sub-subtítulo</h4>
```
<h3>Vinculos</h3>
Los vínculos o enlaces son muy importantes —son los que hacen de la web, la web—. Para implementar un vínculo, necesitas usar un vínculo simple — a —  Para convertir algún texto dentro de un párrafo en un vínculo, sigue estos pasos:

Sintaxis:
```
<a href="https://www.mozilla.org/es-AR/about/manifesto/"
  >Manifesto Mozilla</a
>
```






## CSS
<hr>
-¿Que és?

El CSS  es un lenguaje de programación que se utiliza para dar estilo a los documentos HTML y XML. En otras palabras, el CSS se utiliza para definir cómo se deben mostrar los elementos HTML en una página web. Por ejemplo, el CSS se puede utilizar para cambiar el color de fondo de una página, el tamaño y el tipo de letra del texto, la posición de los elementos en la página.</p>
<hr>
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