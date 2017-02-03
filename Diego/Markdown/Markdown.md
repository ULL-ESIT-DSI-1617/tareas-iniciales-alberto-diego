# Markdown


<div style="text-align:center"><img style="width:50%; height:40%" src="imagenes/portada.png"/></div>

### ¿Qué es Markdown?
Es un lenguaje de marcado ligero creado por John Gruber que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida.
* Se distribuye bajo licencia BSD y se distribuye como plugin (o al menos está disponible) en diferentes sistemas de gestión de contenidos (CMS).
* Markdown convierte el texto marcado en documentos XHTML utlizando html2text creado por Aaron Swartz.
* Fue implementado originariamente en Perl por Gruber, pero desde entonces se ha traducido a multitud de lenguajes de programación, incluyendo PHP, Python, Ruby, Java y Common Lisp.
* No hay una norma definida para Markdown, aparte de la implementación original de John Gruber, que algunos consideran obsoleta. Esto a conducido a fragmentación, pues distintos proveedores han escrito sus propias variantes de Markdown

### Sintaxis de Markdown:

 En este apartado descubrirás la sintaxis Markdown y los conceptos básicos para escribir utilizando este lenguaje de marcado. De hecho, al final del mismo estarás perfectamente capacitado para empezar a utilizar este lenguaje en tus escritos y publicaciones.

 * **Encabezados:** se generan cuando se encuentra una almohadilla antes de texto. Encabezado h1 vendrá precedido de un símbolo "#", Encabezado h2 vendrá precedido de dos símbolos "#" y así sucesivamente.  
```
  # Encabezado h1
 ## Encabezado h2
 ### Encabezado h3
 #### Encabezado h4
 ##### Encabezado h5
 ###### Encabezado h6
 ```
 * **Saltos de línea:** se generan cuando se encuentran dos espacios juntos

 ```
 "Quien fue a Sevilla,  
perdió su silla"
 ```

 * **Citas**: Para citar solo es necesario escribir una cuña antes del texto
 ```
 > La vida es muy corta para aprender alemán. -Tad Marburg
 ```
 * **Texto con énfasis:** Debe agregarse un asterisco para cursiva y dos para negrita
 ```
 *énfasis* (cursiva)
  **énfasis fuerte** (negrita)
 ```
 * **Lístas**

 ```
  * Un elemento en una lista no ordenada
  * Otro elemento en una lista
 ```
 ```
   1. Elemento en una lista numerada u ordenada.
   2. Otro elemento

 ```

 * **Enlaces**
```
 [Texto del enlace aquí](URL "Título del enlace")
 ```

 * **Imágenes**
```
 ![Texto alternativo](URL "Título de la imagen")
 ```

 ### Implementaciones:
 Hay implementaciones de Markdown para muchos lenguajes de programación; también algunas plataformas y frameworks soportan el uso de Markdown.

 Mientras Markdown es muy sencillo y fácil de leer y escribir con un editor de texto plano (como el Bloc de Notas o gedit), hay editores especializados en Markdown (como Haroopad) disponibles para muchos sistemas operativos, como Linux, Mac OS, Windows, Android e iOS. Estos editores también tienen una ventana para previsualizar nuestro documento como si se tratase de un documento WYSIWYG. Ejemplos:
 * PHP: PHP Markdown
 * Python: markdown.py (de webpy.org)
 * Python: (de python.org)
 * Perl: Text::Markdown
 * C#: Markdown.NET
 * Ruby: BlueCloth
 * Java: markdownj, MarkdownPapers
 * JavaScript: Showdown
 * Lua: markdown.lua
 * MultiMarkdown, una versión en Perl de Markdown con ciertas           características extra, así como otras herramientas relacionadas con Markdown.
