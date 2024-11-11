# Introducción a Markdown

## Investiga y contesta a las siguientes preguntas. El resultado lo debes entregar en ficheros en formato markdown

### 1.¿Qué es Markdown y para qué se utiliza?

-El **Markdown** es un lenguaje sencillo sirve para agregar **formatos, imágenes y agregar vínculos o enlaces** con más facilidad al texto simple que estamos editando.
---
### 2.¿Cuáles son las características principales de Markdown que lo hacen diferente de otros lenguajes de marcas de presentación?

-La clave del diseño de **Markdown** es la facilidad de su lectura, que hace que el lenguaje sea fácilmente interpretado, sin lucir como si hubiera sido marcado con etiquetas o instrucciones de estilo, como **RTF o HTML**, los cuales tienen etiquetas que hacen más difícil su lectura e interpretación.
---
### 3.¿Qué aplicaciones o plataformas utilizan Markdown?
```
* TakeNote
* Bear
* Boostnote
* Notepad++
```


---
### 4.¿Cuáles son las etiquetas o símbolos más comunes que se utilizan en Markdown para dar formato a un texto? 

* Los más frecuentes son **cursiva** que se pone con un `*´ al principio y al final de cada palabra (ejemplo: *hola me llamo yeremy*)

* Poner una palabra o un texto en **negrita** que se pone con doble `**´ al pricipio y al final de cada palabra o texto (ejemplo: **hola me llamo yeremy**)

* Las **almohadillas** `#` son uno de los métodos de Markdown para crear encabezados, añadiendo uno por cada nivel.

* Para crear una imagen en Markdown, tenemos que poner la siguiente sintaxis:

EJEMPLO:

![](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

**Instrucciones para incluir una imágen en R Markdown**:

-Primero escribimos `![]´.

-Después escribimos, dentro de los corchetes, el texto alternativo. Este es opcional y solo entra en acción cuando no se puede cargar la imagen correctamente.

-Después escribimos, dentro de los paréntesis, la ubicación del archivo (ya sea una url o una ubicación dentro de algun folder local).

EJEMPLO DE LA SINTAXIS:
``![texto_alternativo](ubicacion_de_la_imagen){width=width height=height}´´

* Para crear un **enlace externo** en Markdown, se utiliza la siguiente sintaxis:
EJEMPLO:
```
[Texto del Enlace](URL-del-enlace)
[www.luisllamas.es](https://www.luisllamas.es) 
```
* Las **citas** se generar utilizando el carácter mayor que `>` al comienzo del bloque de texto.

EJEMPLO:
```
> Un país, una civilización se puede juzgar por la forma en que trata a sus animales.  — Mahatma Gandhi 
```

* Si la cita en cuestión se compone de varios párrafos, deberás añadir el mismo símbolo > al comienzo de cada uno de ellos.

EJEMPLO:
```
> Creo que los animales ven en el hombre un ser igual a ellos que ha perdido de forma extraordinariamente peligrosa el sano intelecto animal.

> Es decir, que ven en él al animal irracional, al animal que ríe, al animal que llora, al animal infeliz. — Friedrich Nietzsche
```


EJEMPLO:
```
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```
* Poner un cuadro para especificar el contenido de cualquier cosa de tal forma que esté clara la información. Por ejemplo: 
(FÚTBOL)
```
* equipaje
* botas
* club
```

### 5.¿Cómo se puede visualizar y convertir un archivo escrito en Markdown a otros formatos, como HTML o PDF?

-Muchas herramientas de edición de MarkDown pueden exportar el archivo MD a un archivo HTML. Solo tienes que abrir archivo MD en estas herramientas, hacer clic en archivo > exportar y seleccionar la opción HTML.
---
### 6.¿Qué ventajas tiene escribir documentación o notas en Markdown frente a usar procesadores de texto como Microsoft Word o Google Docs?

-Por ejemplo; una de las ventajas de usar el Markdown frente a los proesadores de texto es que los archivos **.md** de Markdown, pueden abrirse con cualquier procesador de textos, ya que no dependen de un software o una aplicación en concreto.
---
### 7.¿Existen diferentes "sabores" o variaciones de Markdown?

-Una de las variaciones de Markdown es CommonMark, que es una especificación de Markdown que se desarrolló para abordar la falta de estandarización y coherencia en las implementaciones de Markdown existentes.

Su objetivo es proporcionar una definición unificada y clara del lenguaje, asegurando que el contenido se interprete de manera consistente en diferentes plataformas y aplicaciones.

EJEMPLO:
```
# Encabezado de Nivel 1

Este es un párrafo con **negrita** y *cursiva*.

- Lista desordenada
  - Elemento secundario

1. Lista ordenada
2. Segundo ítem

[Enlace a Google](https://www.google.com)
```
---
### 8.¿Cómo puede ser útil Markdown en el trabajo colaborativo en proyectos de software?
Puede ser útil de manera que sea efetiva y rápida para que el trabajo con los compañeros sea más fluido y eficaz creando documentos, enlazando los documentos a una página web, insertando imágenes, etc... para que se más cómodo tanto para ti, como para el equipo.

---
