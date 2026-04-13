# Guía básica de sintaxis en Markdown 📃✏️
En este repositorio podréis encontrar de forma totalmente gratuita una guía básica de como escribir documentos con el lenguaje de marcado [Markdown](https://es.wikipedia.org/wiki/Markdown).

## Introducción

[Markdown](https://es.wikipedia.org/wiki/Markdown) es un lenguaje de marcado ligero ampliamente utilizado en distintos ámbitos académicos y profesionales debido a su simplicidad y legibilidad. Uno de sus usos más comunes es en plataformas como GitHub, donde se emplea para redactar archivos de documentación como los [README.md](https://es.wikipedia.org/wiki/README), guías de instalación o manuales técnicos dentro de repositorios de software.

En el ámbito académico, además, **Markdown** se utiliza para la redacción de apuntes, trabajos y artículos, especialmente en combinación con herramientas como [Jupyter Notebook](https://es.wikipedia.org/wiki/Proyecto_Jupyter), que permiten integrar texto, código y resultados en un mismo documento. También es habitual en la creación de materiales docentes y presentaciones mediante sistemas como [Pandoc](https://es.wikipedia.org/wiki/Pandoc) o [MkDocs](https://geoinnova.org/blog-territorio/mkdocs-como-crear-y-publicar-documentacion-eficientemente/), que convierten archivos Markdown en documentos PDF, páginas web o presentaciones.

Además, Markdown es frecuente en entornos de investigación y desarrollo por su compatibilidad con sistemas de control de versiones, lo que facilita la colaboración entre equipos. En resumen, su uso se extiende a la documentación técnica, la enseñanza, la investigación y la publicación digital, gracias a su equilibrio entre sencillez y versatilidad.

## 🪧[Encabezados](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings)

Sirven para crear una jerarquía de títulos y subtítulos dentro del documento, de esta forma, por ejemplo, se crea un índice automáticamente en GitHub y es mucho más fácil la navegación por todo el documento creado. 

Se pueden usar escribiendo una almohadilla # seguida de un espacio al inicio para asignar un encabezado de H1 (`# texto`) hasta escribir un H6 (`###### texto`).

⚠️¡IMPORTANTE!⚠️ No hay subtítulos (H7 o superiores) en markdown, solo existen de H1 a H6!

## ✍️*Formatos de texto*

### 🪧[Negrita](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Para poder poner un texto en negrita usaremos dos asteríscos al inicio y dos al final sin dejar espacios (`**texto**`).

- 🧐Ejemplos:

    Este NO es un texto en negrita

    **Este SI es un texto en negrita**

### 🪧[Cursiva](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Se utiliza para enfatizar (poner en cursiva) el texto. Podemos utilizarlo usando el símbolo asterísco (*) o el guión bajo (_) al inicio y al final sin dejar espacios (`*texto*` o `_texto_`).

- 🧐Ejemplos:

    Este NO es un texto enfatizado

    *Este SI es un texto enfatizado*

    _Este también lo es..._

### 🪧[Subrayado](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Para poder escribir un texto subrayado deberemos usar las etiquetas de apertura y cierre (`<ins>texto</ins>`).

- 🧐Ejemplos:

    <ins>Este es un texto totalmente subrayado.</ins>

    <ins>Este texto solo</ins> tiene una parte subrayada.

### 🪧[Tachado](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Para escribir un texto y que esté tachado deberemos utilizar el simbolo ~ dos veces al inicio y dos veces al final del texto (`~~texto~~`).

- 🧐Ejemplos:

    ~~Este texto está totalmente tachado~~

    Este texto solo tiene esta ~~porción~~ parte tachada

### 🪧[Subíndice](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Cuando queremos escribir un texto con un subíndice (letra o número) del estilo A<sub>B</sub>, debermos usar estas etiquetas (`A<sub>B</sub>`) para especificar el texto que se mostrará como subíndice.

- 🧐Ejemplos:

    A<sub>B</sub>

    2<sub>3</sub>

    α<sub>π</sub>

### 🪧[Superíndice](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Igual que hemos visto con el subíndice, para poder escribir un superíndice del estilo 2<sup>3</sup> debermos usar las etiquetas (`2<sup>3</sup>`) para especificar el texto que se mostrará como superíndice.

- 🧐Ejemplos:

    A<sup>B</sup>

    2<sup>3</sup>

    α<sup>π</sup>


## 🪧[Citas](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text)

Sirven para citar un texto.

Podemos citar texto usando el símbolo de mayor que (>) al inicio.

- 🧐Ejemplos:

    Texto que no es una Cita
    > Texto que es una Cita

## 🪧[Listas](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists)

Se utilizan para poder mostrar elementos de una lista.

Las listas pueden ser:

- <ins>Numeradas</ins>: podemos usar números con un punto seguido al inicio: 1.,2.,3., dejando un espacio entre el texto.
- <ins>No numeradas</ins>: podemos usar * al inicio dejando un espacio antre el texto.

- 🧐Ejemplos:

    <ins>Lista Numerada</ins>:

    1. Primero
    2. segundo
    3. Tercero

    <ins>Lista no numerada</ins>:

    * Primero
    * Segundo
    * Tercero




<!-- PLANTILLA PARA COPIAR -->
# PLANTILLA PARA COPIAR
# 🪧[TÍTULO]()

DESCRIPCIÓN

- 🧐Ejemplos:

    AAA


# Más información...
* [Sintaxis básica de redacción y formato - GitHub Docs](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [Guía de referéncia *The Markdown Guide*](https://www.markdownguide.org/)
