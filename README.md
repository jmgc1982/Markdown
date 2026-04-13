# Guía básica de sintaxis en Markdown 📃✏️
En este repositorio podréis encontrar de forma totalmente gratuita una guía básica de como escribir documentos con el lenguaje de marcado [Markdown](https://es.wikipedia.org/wiki/Markdown).

## 📃Introducción

[Markdown](https://es.wikipedia.org/wiki/Markdown) es un lenguaje de marcado ligero ampliamente utilizado en distintos ámbitos académicos y profesionales debido a su simplicidad y legibilidad. Uno de sus usos más comunes es en plataformas como GitHub, donde se emplea para redactar archivos de documentación como los [README.md](https://es.wikipedia.org/wiki/README), guías de instalación o manuales técnicos dentro de repositorios de software.

En el ámbito académico, además, **Markdown** se utiliza para la redacción de apuntes, trabajos y artículos, especialmente en combinación con herramientas como [Jupyter Notebook](https://es.wikipedia.org/wiki/Proyecto_Jupyter), que permiten integrar texto, código y resultados en un mismo documento. También es habitual en la creación de materiales docentes y presentaciones mediante sistemas como [Pandoc](https://es.wikipedia.org/wiki/Pandoc) o [MkDocs](https://geoinnova.org/blog-territorio/mkdocs-como-crear-y-publicar-documentacion-eficientemente/), que convierten archivos Markdown en documentos PDF, páginas web o presentaciones.

Además, Markdown es frecuente en entornos de investigación y desarrollo por su compatibilidad con sistemas de control de versiones, lo que facilita la colaboración entre equipos. En resumen, su uso se extiende a la documentación técnica, la enseñanza, la investigación y la publicación digital, gracias a su equilibrio entre sencillez y versatilidad.

## 🪧[Encabezados](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings)

Sirven para crear una jerarquía de títulos y subtítulos dentro del documento, de esta forma, por ejemplo, se crea un índice automáticamente en GitHub y es mucho más fácil la navegación por todo el documento creado. 

Se pueden usar escribiendo una almohadilla # seguida de un espacio al inicio para asignar un encabezado de H1 (`# texto`) hasta escribir un H6 (`###### texto`).

⚠️¡IMPORTANTE!⚠️: No hay subtítulos H7 o superiores en markdown, solo existen de H1 a H6.

## ✍️Formatos de texto

### ✍️[Negrita](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Para poder poner un texto en negrita usaremos dos asteríscos al inicio y dos al final del texto sin dejar espacios entre ellos (`**texto**`).

- 🧐Ejemplos:

    Este NO es un texto en negrita

    **Este SI es un texto en negrita**

### ✍️[Cursiva](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Se utiliza para enfatizar el texto. Podemos utilizarlo usando el símbolo asterísco (`*`) o el guión bajo (`_`) al inicio y al final sin dejar espacios (`*texto*` o `_texto_`).

- 🧐Ejemplos:

    Este NO es un texto enfatizado

    *Este SI es un texto enfatizado (usando `*`)*

    _Este también lo es... (usando `_`)_ 

### ✍️[Combinaciones anidadas](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Existen tambien una serie de combinaciones cuando el texto debe mostrarse en cursiva y negrita mezclados o al mismo tiempo:

- 🧐Ejemplos:

    Texto en negrita pero incluye una parte en cursiva (`**texto1_texto2_texto3**`, donde todo el texto estará en negrita pero `texto2` además estará en cursiva): 
    
    **Este texto es _extremadamente_ importante**

    Todo en negrita y en cursiva (usar tres asteriscos al inicio y final `***texto***`):

    ***Todo este texto es importante***

### ✍️[Subrayado](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Para poder escribir un texto subrayado deberemos usar las etiquetas de apertura y cierre (`<ins>texto</ins>`).

- 🧐Ejemplos:

    <ins>Este es un texto totalmente subrayado.</ins>

    <ins>Este texto solo</ins> tiene una parte subrayada.

### ✍️[Tachado](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Para escribir un texto y que esté tachado deberemos utilizar el simbolo ~ dos veces al inicio y dos veces al final del texto sin espacios entre ellos (`~~texto~~`). 

El símbolo ~ (tilde o virgulilla) se puede escribir de distintas formas según el sistema operativo y el teclado:

- <ins>Windows</ins>: mantén pulsada la tecla `ALT` y escribe `126` en el teclado numérico `ALT+126`.
- <ins>MacOS</ins>: Pulsa `Alt (⌥) + ñ`.
- <ins>Linux</ins>: Depende del layout del teclado, pero en español suele ser `Alt Gr + 4`.

El símbolo `~` se usa mucho en programación y documentación o en rutas tipo `~/carpeta` en sistemas Unix.

- 🧐Ejemplos:

    ~~Este texto está totalmente tachado~~

    Este texto solo tiene esta ~~porción~~ parte tachada

### ✍️[Subíndice](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Cuando queremos escribir un texto con un subíndice (letra o número) del estilo A<sub>B</sub>, debermos usar estas etiquetas (`A<sub>B</sub>`) para especificar el texto que se mostrará como subíndice.

- 🧐Ejemplos:

    A<sub>B</sub>

    2<sub>3</sub>

    α<sub>π</sub>

### ✍️[Superíndice](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text)

Igual que hemos visto anteriormente con el subíndice, para poder escribir un superíndice del estilo 2<sup>3</sup> debermos usar las etiquetas (`2<sup>3</sup>`) para especificar el texto que se mostrará como superíndice.

- 🧐Ejemplos:

    A<sup>B</sup>

    2<sup>3</sup>

    α<sup>π</sup>


## 🪧[Citas](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text)

Sirven para citar un texto, por ejemplo de un autor concreto, de un libro, etc.

Podemos citar texto usando el símbolo de mayor que (`>`) al inicio.

- 🧐Ejemplos:

    Texto que no es una Cita
    > Texto que es una Cita

# 🪧[Código fuente](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-code)

Puede destacar código o comandos dentro de una oración con comillas invertidas simples(` `` `). No se dará formato al texto dentro de las comillas invertidas. 

- 🧐Ejemplos:

    Usar `git status` para ver el estado actual del repositorio.

Para dar formato al código o al texto en su propio bloque diferenciado, use tres comillas invertidas (` ``` ``` `).

- 🧐Ejemplo:

Algunos comandos básicos de Git:
```
git status
git add .
git commit -m "mensaje"
```

## 🪧[Listas](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists)

Se utilizan para poder mostrar elementos en un formato de lista.

Las listas pueden ser:

- <ins>Numeradas</ins>: podemos usar números con un punto seguido al inicio: `1.`,`2.`,`3.`, dejando un espacio entre estos y el texto.
- <ins>No numeradas</ins>: podemos usar `*`, `-` o `+` al inicio dejando un espacio antes del texto.

- 🧐Ejemplos:

    <ins>Lista Numerada</ins>:

    1. Primer elemento
    2. segundo elemento
    3. Tercer elemento

    <ins>Lista no numerada</ins>:

    * Primer elemento
    - Segundo elemento
    + Tercer elemento

Para <ins>**listas anidadas**</ins>, deberemos usar el tabulador para especificar los niveles y así tendremos la jerarquía anidada dentro de las listas numeradas y no numeradas.

- 🧐Ejemplos:

    <ins>Lista Numerada anidada</ins>:

    1. Elemento 1
        1. Elemento 1.1
            1. Elemento 1.1.1
        2. Elemento 1.2
    2. Elemento 2
    3. Elemento 3

    <ins>Lista no numerada anidada</ins>:

    * Elemento 1
        * Elemento 1.1
            * Elemento 1.1.1
            * Elemento 1.1.2
        * Elemento 1.2
    * Elemento 2
    * Elemento 3

## 🪧[Listas de tareas](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)

Para crear una lista de tareas, se debe añadir como prefijo un guion y un espacio seguido de apertura y cierre de corchetes dejando un espacio entre ellos y finalmente otro espacio para seguir con el texto del elemento (`- [ ] elemento`). 

Para marcar una tarea como completada, usar una x (`[x]`). Si una descripción del elemento de lista de tareas comienza por un paréntesis, deberá escaparla con `\` para poder verlo correctamente:

- 🧐Ejemplos:

    - [x] Primer elemento de la lista de tareas (completada :tada:)
    - [ ] Segundo elemento de la lista de tareas
    - [ ] \(Opcional) Tercer elemento de la lista de tareas

## 🪧[Enlaces](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)

Puede crear un vínculo insertado ajustando el texto del vínculo entre corchetes [ ] y ajustando la dirección URL entre paréntesis ( ) (`[texto del enlace](URL)`)

- 🧐Ejemplos:

    [Google](https://www.google.com/)

    [Wikipedia](https://es.wikipedia.org/)

## 🪧[Enlaces de sección](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#section-links)

A parte de utilizar los enlaces para enlazar páginas externas, se puede vincular directamente a cualquier sección del documento que tenga un encabezado (H1 a H6). 

Para ver el delimitador generado automáticamente en un archivo representado, mantenga el puntero sobre el encabezado de sección para exponer el icono de ⛓️‍💥 y haga clic en el icono para mostrar la URL del delimitador en el explorador. El delimitador será el simbolo # y lo que viene después.

- 🧐Ejemplos:

    Por ejemplo, la URL del apartado "Encabezados" de este documento es:

    `URL#Introducción`

    El delimitador generado es `#Introducción`

    Podemos ir a este apartado usando este [**enlace**](#introducción).

    O podemos ir al apartado de **"subrayado"** usando este otro [**enlace**](#️subrayado).

## 🪧[Imágenes](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images)

Se puede mostrar una imagen escribiendo `!` y ajustando el texto alternativo dentro de `[ ]`. El texto alternativo es un texto corto equivalente a la información de la imagen. Finalmente, se debe de indicar el vínculo URL de la imagen entre paréntesis `()`. El formato es: `![texto_alt](URL)`. 

También se puede mostrar una imagen almacenada en el repositorio de GitHub. Primero deberemos agregar esta imagen en el repositorio, luego ver que URL nos generar GitHub y finalmente enlazarla.

- 🧐Ejemplos:

    Imágen con URL externa:

    ![Octocat sonriendo y levantando un tentáculo](https://myoctocat.com/assets/images/base-octocat.svg)

    Imágen en GitHub con URL interna:

    ![imágen almacenada en el repositorio](https://github.com/jmgc1982/Markdown/blob/main/fork-me.jpg)

## 🪧[Tablas](https://www.markdownguide.org/extended-syntax/#tables)

En Markdown podemos crear tablas de forma sencilla usando `|` (barras verticales) y `-` (guiones). La primera fila se utiliza para indicar la cabecera de la tabla.

- 🧐Ejemplos:

    | Columna 1 | Columna 2 | Columna 3 |
    |-----------|-----------|-----------|
    | Dato A    | Dato B    | Dato C    |
    | Dato D    | Dato E    | Dato F    |

## 🪧[HTML](https://www.markdownguide.org/basic-syntax/#html)

Muchas aplicaciones de Markdown permiten usar etiquetas HTML en texto con formato Markdown. Esto resulta útil si prefieres ciertas etiquetas HTML a la sintaxis de Markdown. 

Por ejemplo, a algunas personas les resulta más fácil usar etiquetas HTML para imágenes. Usar HTML también es útil cuando necesitas cambiar los atributos de un elemento, como especificar el color del texto o cambiar el ancho de una imagen.

Para usar HTML, inserta las etiquetas en el texto de tu archivo con formato Markdown.

- 🧐Ejemplos:

    Esta **palabra** está en negrita. (Markdown `**palabra**`)

    Esta <em>palabra</em> está en cursiva. (HTML `<em>palabra</em>`)


# Más información...
* [Sintaxis básica de redacción y formato - GitHub Docs](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [Guía de referéncia *The Markdown Guide*](https://www.markdownguide.org/)
