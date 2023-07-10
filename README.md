# Curso Basico de HTML de HolaMundo en Youtube

> Link del curso: [aqui](https://www.youtube.com/watch?v=MJkdaVFHrto)

### _Antes de iniciar, enlistar algunas herramientas que estoy utilizando para llevar este curso:_

1. **Web para escribir Markdown de este Readme:** [link](https://stackedit.io/app#)
2. **IDE:** IntelliJ IDEA, de jetbrains (requiere licencia)

### *Ahora si! A sacarle el jugo a esta nueva habilidad 🚀*

------

## ¿QUE ES HTML?

> Hyper Text Markup Language

- Es el lenguaje estandar para crear páginas web.
- Describe la estructura de la página web. Le va a dar un orden.
- Le indica al explorador que y como mostrarlo
- Consiste de etiquetas
- Las etiquetas indican Parrafos, Titulos, Vinculos, Secciones, Cabeceras, etc...

---

## ¿QUE ES UNA ETIQUETA?

**Consta de 3 partes:**

- **Apertura de la etiqueta:** donde tenemos que utilizar los signos "**<**" y "**>**" y dentro de esto, el nombre de la
  etiqueta. Por ejemplo:
  `<soy-una-etiqueta>`
- **Contenido de la etiqueta:** donde nosotros tenemos que colocar el contenido dentro de la etiqueta.
  Ejemplo:`Acá va el contenido de la etiqueta`.
- **Cierre de la etiqueta:** es casí que igual a la apertura, con la única diferencia que después del signo "<" a este
  le sigue un slash hacia adelante o pleca "/". Ejemplo: `</soy-una-etiqueta>`

**Ejemplo consolidado de etiqueta:**

    # Ejemplo de etiqueta:
    
    <soy-una-etiqueta>
       Acá va el contenido de la etiqueta
    </soy-una-etiqueta>

---

### ESTRUCTURA DE HTML

    <html>
    <head>
        <title> El título de mi página </title>
    </head>
    <body>
        <h1> Un heading o título </h1>
        <p> Un párrafo </p>
    </body>
    </html>

- **html:** siempre va al inicio
- **head:** nos sirve para agregar más descripciones, que no necesariamente el usuario va a ver, pero que nos sirve para
  incluir otro tipo de codigo a nuestra página web
- **body:** en la cual vamos a colocar todo el contenido que va a ser visible para el usuario 🙍🏼‍♂️. En el ejemplo
  vemos:
    - **"h1"** que significa: un Heading o Titulo
    - **"p"** que significa un párrafo

![img.png](img.png)

---

### DIFINICIONES DE ETIQUETAS

- `<span>`: La etiqueta <span> en HTML se utiliza para aplicar estilos o manipular porciones específicas de texto dentro
  de un elemento más grande. Esta etiqueta no tiene un significado semántico propio, sino que se utiliza como un
  contenedor genérico en línea. Puede ser útil para aplicar estilos personalizados o realizar manipulaciones con
  JavaScript.

  La etiqueta `<span>` se utiliza de la siguiente manera:
  > `<span>Texto de ejemplo</span>`

  Puedes aplicar estilos al texto contenido dentro de la etiqueta `<span>` utilizando CSS o manipularlo dinámicamente
  utilizando JavaScript. También puedes combinar <span> con otras etiquetas HTML para lograr el efecto deseado.

  Es importante tener en cuenta que la etiqueta `<span>` no agrega ninguna estructura semántica a tu contenido, por lo
  que es preferible utilizarla en conjunto con etiquetas más descriptivas cuando sea posible.

- `<br>`: en HTML se utiliza para insertar un salto de línea en el contenido. Se utiliza principalmente para separar
  visualmente elementos en diferentes líneas o crear espacios en blanco dentro de un texto. Ejemplo:

      Esto es un texto.<br>
      Esto está en una nueva línea.
  _En el ejemplo anterior, el texto "Esto es un texto." se muestra en una línea, y luego la etiqueta `<br>` se utiliza para
  insertar un salto de línea antes de "Esto está en una nueva línea.", creando así una nueva línea en la salida visual._