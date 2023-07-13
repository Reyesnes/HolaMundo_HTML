# Curso Basico de HTML de HolaMundo en Youtube

> Link del curso: [aqui](https://www.youtube.com/watch?v=MJkdaVFHrto)

### _Antes de iniciar, enlistar algunas herramientas que estoy utilizando para llevar este curso:_

1. **Web para escribir Markdown de este Readme:** [link](https://pandao.github.io/editor.md/en.html)
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

Una etiqueta HTML es una estructura básica utilizada para marcar y dar formato al contenido en un documento HTML. En
HTML, las etiquetas son elementos clave que se utilizan para definir la estructura, el estilo y el comportamiento de una
página web.

Las etiquetas HTML están compuestas por corchetes angulares (< y >) y se dividen en dos partes: la etiqueta de apertura
y la etiqueta de cierre. La etiqueta de apertura indica el inicio de un elemento, y la etiqueta de cierre indica el
final del elemento. El contenido que se encuentra entre las etiquetas es el contenido que se mostrará en la página web.

Por ejemplo, la etiqueta `<p>` se utiliza para definir un párrafo en HTML. La etiqueta de apertura `<p>` indica el
inicio
del párrafo, y la etiqueta de cierre `</p>` indica el final del párrafo. El texto o contenido que se encuentra entre
estas
etiquetas será tratado como un párrafo y se mostrará en una línea separada.

Además, hay etiquetas HTML que no requieren una etiqueta de cierre, como la etiqueta `<br>` para un salto de línea o la
etiqueta `<img>` para insertar imágenes. Estas etiquetas se llaman etiquetas vacías o autónomas.

Las etiquetas HTML son fundamentales para crear la estructura y el diseño de una página web, y se combinan con atributos
y estilos para lograr la presentación deseada.

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
  _En el ejemplo anterior, el texto "Esto es un texto." se muestra en una línea, y luego la etiqueta `<br>` se utiliza
  para
  insertar un salto de línea antes de "Esto está en una nueva línea.", creando así una nueva línea en la salida visual._


- `<a>`: se utiliza para crear un enlace o hipervínculo a otra página web, archivo o ubicación dentro
  de la misma página. Es una de las etiquetas fundamentales para la navegación y la interacción en la web.
  La etiqueta `<a>` se utiliza de la siguiente manera:

      <a href="url">Texto del enlace</a>

  La parte más importante de la etiqueta `<a>` es el atributo `href`, que especifica la dirección o URL de destino del
  enlace. Puede ser una URL completa, una ruta relativa a la página actual o un identificador interno de un elemento en
  la misma página.

  Cuando un usuario hace clic en un enlace creado con la etiqueta `<a>`, el navegador se dirigirá a la URL especificada
  en el atributo `href`. Si la URL apunta a otra página web, el navegador cargará esa página. Si la URL es un archivo,
  se puede descargar o abrir según el tipo de archivo. Si la URL es un identificador interno, el navegador se desplazará
  automáticamente a la ubicación correspondiente en la misma página.

  Además del atributo `href`, la etiqueta `<a>` también puede tener otros atributos, como target para especificar cómo
  se
  abrirá el enlace (en la misma ventana, en una nueva ventana o en una pestaña nueva) y title para proporcionar
  información adicional al usuario cuando pasa el cursor sobre el enlace.

  Al momento de insertar una URL, podemos definir que nos abra el link en una nueva pestaña, y no en la misma pestaña.
  Para esto podemos agregar una nueva propiedad a la etiqueta de `<a>`. La propiedad se llama `target` y la agregamos
  como prefijo antes de la propiedad `href` y la definimos de esta manera:

      <a target="blank" href="https://www.youtube.com"> Ir a Youtube </a>
- `<img/>`: e utiliza para insertar una imagen en una página web. Es una etiqueta de autocierre, lo que significa que no
  tiene una etiqueta de cierre correspondiente.

  La etiqueta `<img/>` se utiliza de la siguiente manera:

      <img src="ruta_de_la_imagen" alt="texto_alternativo" />

  El atributo `src` especifica la ruta o URL de la imagen que se desea mostrar. Puede ser una URL completa o una ruta
  relativa a la ubicación del archivo HTML.

  El atributo alt proporciona un texto alternativo para la imagen. Este texto se mostrará si la imagen no se puede
  cargar correctamente o si el usuario está utilizando un lector de pantalla para acceder a la página. El texto
  alternativo también es útil para mejorar la accesibilidad de la página y brindar información adicional sobre la
  imagen.

  Además de los atributos `src` y `alt`, la etiqueta `<img/>` también puede tener otros atributos opcionales,
  como `width` y
  `height` para especificar el tamaño de la imagen en píxeles, y title para proporcionar un texto descriptivo cuando el
  usuario pasa el cursor sobre la imagen.

  > > >  La etiqueta <img/> es esencial para agregar elementos visuales a una página web, como logotipos, ilustraciones o
  fotografías. Al utilizar esta etiqueta correctamente, puedes mejorar la apariencia y la experiencia visual de tu sitio
  web.