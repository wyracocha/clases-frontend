# Conociendo la tecnología
## HTML 5
> HTML 5 (HyperText Markup Language, versión 5) es la quinta revisión importante del lenguaje básico de la World Wide Web, HTML. HTML5 especifica dos variantes de sintaxis para HTML: una «clásica», HTML (text/html), conocida como HTML5, y una variante XHTML conocida como sintaxis XHTML 5 que deberá servirse con sintaxis XML (application/xhtml+xml). Esta es la primera vez que HTML y XHTML se han desarrollado en paralelo. La versión definitiva de la quinta revisión del estándar se publicó en octubre de 2014

Eso dice wikipedia, en la práctica nos encontraremos que HTML 5 es la suma de un conjunto, stack, de tecnologías: HTML, CSS y Javascript. <br>
¿Qué lo hace especial?. Del lado de HTML es el como ahora se programa una web, es decir,
ahora los elementos que componen una web tienen un sentido lógico. Del lado de CSS tenemos muchas mejoras: sombras, posicionamiento de objetos y selectores son solo una parte del lenguaje. Finalmente Javascript es la parte más desarrollada pues se han incluido muchas tecnologías que hacen el trabajo más ordenado.

## Ejemplo de una web con HTML5
```html5
  <!DOCTYPE html>
  <html lang="es">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi web de ejemplo</title>
  </head>
  <body>
    <header>
      Header de la página
    </header>
    <section>
      Sección 1
    </section>
    <section>
      Sección 2
    </section>
    <footer>
      Pie de página
    </footer>
  </body>
  </html>
```
## Partes de la web

### DOCTYPE
Especifica al navegador que se usará HTML5 como lenguaje en la web.
### Lang
Indica el lenguaje de la web, para que pueda ser traducida por los navegadores de ser necesario.
### HEAD
Bloque donde se inserta información adicional de la web y se agregan dependencias.
### BODY
Sección donde se introduce todo el código de nuestra web: imágenes, texto informativo, videos, etc.