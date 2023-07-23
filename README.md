# Curso Basico de HTML de HolaMundo en Youtube

> Link del curso: [aqui](https://www.youtube.com/watch?v=MJkdaVFHrto)

### _Antes de iniciar, enlistar algunas herramientas y referencias que estoy utilizando para realizar este curso:_

1. **Web para escribir Markdown de este Readme:** [link](https://pandao.github.io/editor.md/en.html)
2. **IDE:** IntelliJ IDEA, de jetbrains (requiere licencia) o el de preferencia
3. https://www.learn-html.org/
3. https://developer.mozilla.org/es/docs/Web/HTML/Element
4. https://www.hazlodigital.com/herramientas-recursos-gratis/
5. https://www.hazlodigital.com/herramientas-recursos-gratis/tech-stack-para-tu-startup/

### *Ahora si! A sacarle el jugo 🚀*

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
  se abrirá el enlace (en la misma ventana, en una nueva ventana o en una pestaña nueva) y title para proporcionar
  información adicional al usuario cuando pasa el cursor sobre el enlace.

  Al momento de insertar una URL, podemos definir que nos abra el link en una nueva pestaña, y no en la misma pestaña.
  Para esto podemos agregar una nueva propiedad a la etiqueta de `<target="blank">`. La propiedad se llama `target` y la
  agregamos como prefijo antes de la propiedad `href` y la definimos de esta manera:

      <a target="blank" href="https://www.youtube.com"> Ir a Youtube </a>
- `<img/>`: se utiliza para insertar una imagen en una página web. Es una etiqueta de autocierre, lo que significa que
  no tiene una etiqueta de cierre correspondiente.

  La etiqueta `<img/>` se utiliza de la siguiente manera:

      <img src="ruta_de_la_imagen" alt="texto_alternativo" />

  Ejemplo:

      <img src="img/coffee.png"/>

  El atributo `src` especifica la ruta o URL de la imagen que se desea mostrar. Puede ser una URL completa o una ruta
  relativa a la ubicación del archivo HTML.

  El atributo `alt` proporciona un texto alternativo para la imagen. Este texto se mostrará si la imagen no se puede
  cargar correctamente o si el usuario está utilizando un lector de pantalla para acceder a la página. El texto
  alternativo también es útil para mejorar la accesibilidad de la página y brindar información adicional sobre la
  imagen.

  Además de los atributos `src` y `alt`, la etiqueta `<img/>` también puede tener otros atributos opcionales,
  como `width` y `height` para especificar el tamaño de la imagen en píxeles, y title para proporcionar un texto
  descriptivo cuando el usuario pasa el cursor sobre la imagen.

  > > > La etiqueta <img/> es esencial para agregar elementos visuales a una página web, como logotipos, ilustraciones o
  fotografías. Al utilizar esta etiqueta correctamente, puedes mejorar la apariencia y la experiencia visual de tu sitio
  web.

  También, se pueden especificar propiedades de tamaño dentro de la etiqueta `<img/>`, como por ejemplo:
    - `width`: Esta propiedad especifica el ancho de la imagen en píxeles. Puedes usarla para ajustar el
      tamaño horizontal de la imagen en la página
    - `height`: Esta propiedad indica la altura de la imagen en píxeles. Te permite ajustar el tamaño vertical de la
      imagen.

  Por ejemplo:

      <img src="img/coffee.png" height="200" width="250"/>

## FORMULARIOS

Un formulario en HTML es una sección de una página web que permite a los usuarios enviar datos o interactuar con el
sitio web. Es una herramienta fundamental para la recopilación de información y la interacción del usuario con el
contenido en línea.

Los formularios se crean utilizando la etiqueta `<form>` en HTML, y dentro de esta etiqueta se agregan diversos
elementos de entrada, como campos de texto, botones, casillas de verificación, menús desplegables, entre otros.

- `<form>`: Es la etiqueta principal que indica el inicio y el final del formulario. Los elementos del formulario deben
  estar contenidos dentro de esta etiqueta.

Un formulario suele constar de los siguientes elementos principales:

#### 1. Campos de entrada:

Estos elementos permiten a los usuarios ingresar datos, como texto, números, fechas, correos
electrónicos, etc. Algunos ejemplos de campos de entrada son `<input>`, `<textarea>`, y `<select>` (para menús
desplegables).

- `<input>`: El campo de entrada de `<input>` puede tener diferentes tipos de acuerdo con el atributo "type" que se le
  asigne. Algunos de los tipos más comunes son:

| Tipos    | Descripción                                                                                                                                 |
|----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| text     | Crea un campo de entrada de texto de una sola línea donde los usuarios pueden ingresar texto, números o cualquier otro dato de texto.       |
| password | Similar al tipo "text", pero oculta los caracteres ingresados, mostrando asteriscos o puntos, para proteger la privacidad de la contraseña. |
| email    | Crea un campo de entrada para recopilar direcciones de correo electrónico válidas.                                                          |
| number   | Crea un campo de entrada para ingresar números, ya sean enteros o decimales.                                                                |
| date     | Crea un campo de entrada para obtener fechas específicas en formato "AAAA-MM-DD".                                                           |
| checkbox | Crea una casilla de verificación que permite a los usuarios seleccionar una o varias opciones                                               |
| radio    | Crea botones de opción para permitir a los usuarios seleccionar una opción entre varias.                                                    |
| submit   | Crea un botón de envío que permite a los usuarios enviar el formulario.                                                                     |
| reset    | Crea un botón para restablecer el formulario a sus valores predeterminados.                                                                 |
| file     | Crea un campo de entrada para seleccionar archivos del dispositivo del usuario.                                                             |

- `<textarea>`: Crea un campo de texto de varias líneas donde los usuarios pueden escribir comentarios o información más
  extensa que en un campo de texto de una sola línea.

  Ejemplo:

      <label for="comentarios">Comentarios:</label>
      <textarea id="comentarios" name="comentarios" rows="4" cols="40"></textarea>

  Además, este campo de entrada, puede contener elementos o propiedades de dimensión como:

    - _cols_: para indicar la cantidad de columnas o _ancho_ del cuadro de texto
    - _rows_: para indicar la cantidad de filas o _alto_ del cuadro de texto

    Ejemplo:
        
      <form action="/procesar_datos" method="post">
        <label for="comentarios">Comentarios:</label>
        <br>
        <textarea id="comentarios" name="comentarios" cols="40" rows="6" required></textarea>
        <br>
        <input type="submit" value="Enviar">
      </form>


- `<select>`: Crea un menú desplegable que permite a los usuarios seleccionar una opción de una lista.

  Ejemplo:

      <label for="ciudad">Ciudad:</label>
      <select id="ciudad" name="ciudad">
        <option value="madrid">Madrid</option>
        <option value="barcelona">Barcelona</option>
        <option value="valencia">Valencia</option>
      </select>

    - `<button>`: Crea botones personalizados que pueden realizar acciones específicas dentro del formulario.

      Ejemplo:

          <button type="button" onclick="saludar()">Saludar</button>

    - `<fieldset>` y `<legend>`: Estos elementos se utilizan juntos para agrupar elementos de entrada relacionados
      visualmente y proporcionar una leyenda o título descriptivo para el grupo.

      Ejemplo:

          <fieldset>
            <legend>Datos Personales</legend>
            <!-- Aquí se agregarían los campos de entrada relacionados -->
            </fieldset>

    - `<datalist>`: Se utiliza junto con el elemento `<input type="text">` para proporcionar una lista de opciones
      sugeridas al usuario mientras escribe en el campo

      Ejemplo:

          <label for="busqueda">Buscar:</label>
          <input type="text" id="busqueda" name="busqueda" list="opciones">
          <datalist id="opciones">
            <option value="Opción 1">
            <option value="Opción 2">
            <option value="Opción 3">
          </datalist>

#### 2. Etiquetas:

Se utilizan para describir los campos de entrada y proporcionar información sobre qué tipo de datos se
debe ingresar.

- `<label>`: Se utiliza para asociar una etiqueta descriptiva con un campo de entrada. Ayuda a los usuarios a comprender
  qué se espera que ingresen en el campo y mejora la experiencia de usuario al permitir que hagan clic en la etiqueta
  para enfocar el campo de entrada correspondiente.

  Ejemplo:

      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" name="nombre" required>

- `<legend>`: Se utiliza dentro de la etiqueta `<fieldset>` para proporcionar una leyenda o título descriptivo para un
  grupo de campos de entrada relacionados. Ayuda a organizar y agrupar campos de manera visualmente coherente.

  Ejemplo:

      <fieldset>
        <legend>Datos Personales</legend>
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
        <br>
        <!-- Otros campos de entrada relacionados aquí -->
      </fieldset>

  Texto dentro del formulario: Además de las etiquetas <label> y <legend>, también puedes utilizar texto normal dentro
  del formulario para proporcionar instrucciones, indicaciones o descripciones sobre los campos de entrada.

  Ejemplo:

      <form>
        <p>Por favor, ingrese su nombre y correo electrónico:</p>
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
        <br>
        <label for="correo">Correo electrónico:</label>
        <input type="email" id="correo" name="correo" required>
        <br>
        <input type="submit" value="Enviar">
      </form>


#### 3.Botones:

Los botones, como `<input type="submit">` y `<input type="reset">`, se utilizan para enviar los datos
ingresados o restablecer el formulario, respectivamente.

Cuando un usuario completa y envía un formulario, los datos ingresados se pueden procesar en el servidor web o
mediante código del lado del cliente (como JavaScript). Esto permite que los sitios web interactúen con los usuarios,
recopilen
información y realicen acciones específicas en función de los datos enviados.

Los formularios son una parte esencial de la experiencia del usuario en la web, ya que facilitan la comunicación
bidireccional entre el usuario y el sitio web, lo que permite una amplia gama de interacciones en línea, desde iniciar
sesión en una cuenta hasta enviar comentarios o realizar compras en línea.

Otras propiedades que pueden contener los elementos del formulario son:

- `name`: el cuál se utiliza para identificar el campo de entrada cuando el formulario se envía al servidor o se procesa
  mediante código del lado del cliente (como JavaScript). Cada campo de entrada debe tener un nombre único dentro del
  formulario para que los datos ingresados se puedan identificar y manipular adecuadamente. Ejemplo:

      <form action="/procesar_datos" method="post">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
        <br>
        <label for="correo">Correo electrónico:</label>
        <input type="email" id="correo" name="correo" required>
        <br>
        <input type="submit" value="Enviar">
      </form>

  _En este ejemplo, los campos de entrada para el nombre y el correo electrónico tienen las propiedades name
  establecidas
  como "nombre" y "correo", respectivamente. Cuando el formulario se envía al servidor, los datos ingresados en estos
  campos se enviarán con los nombres "nombre" y "correo", lo que permite que el servidor identifique y procese cada dato
  individualmente._


- `placeholder`: se utiliza para proporcionar una pista o ejemplo breve sobre el tipo de datos que se debe ingresar en
  el campo. Esta propiedad muestra un texto en gris claro dentro del campo antes de que el usuario ingrese cualquier
  información. Sirve como una guía para el usuario sobre qué se espera que ingrese en el campo. Así:

      <form action="/suscribirse" method="post">
        <label for="correo">Ingrese su correo electrónico:</label>
        <input type="email" id="correo" name="correo" placeholder="usuario@example.com" required>
        <br>
        <input type="submit" value="Suscribirse">
      </form>

- `type`: se utiliza en los elementos del formulario en HTML para especificar el tipo de datos que se permite ingresar
  en un campo de entrada. Dependiendo del valor del atributo "type", el campo de entrada puede aceptar diferentes tipos
  de datos, como texto, números, fechas, correos electrónicos, contraseñas, entre otros.

  Aquí están algunos de los valores más comunes para la propiedad "type":

    - `text`: Este es el valor predeterminado. Se utiliza para campos de entrada de texto donde los usuarios pueden
      ingresar cualquier tipo de texto, como nombres, comentarios o descripciones.

      _Ejemplo_:

          <label for="nombre">Nombre:</label>
          <input type="text" id="nombre" name="nombre" required>

    - `email`: Este tipo de campo de entrada se utiliza para recopilar direcciones de correo electrónico válidas.

      _Ejemplo_:

          <label for="correo">Correo electrónico:</label>
          <input type="email" id="correo" name="correo" required>

    - `number`: Se utiliza para campos que aceptan solo números, ya sean enteros o decimales.

      _Ejemplo_:

          <label for="edad">Edad:</label>
          <input type="number" id="edad" name="edad" min="18" max="100" required>

    - `date`: Sirve para obtener fechas específicas en formato "AAAA-MM-DD".

      _Ejemplo_:

          <label for="fecha_nacimiento">Fecha de nacimiento:</label>
          <input type="date" id="fecha_nacimiento" name="fecha_nacimiento" required>

    - `password`: Se usa para campos de contraseñas, donde el texto ingresado se oculta por puntos o asteriscos para
      proteger la privacidad del usuario.

      _Ejemplo_:

          <label for="contrasena">Contraseña:</label>
          <input type="password" id="contrasena" name="contrasena" required>

    - `checkbox`: Se utiliza para crear casillas de verificación que permiten a los usuarios seleccionar una o varias
      opciones.

      _Ejemplo_:

          <label for="acepto_terminos">Acepto los términos y condiciones</label>
          <input type="checkbox" id="acepto_terminos" name="acepto_terminos" required>

Estos son solo algunos ejemplos de los valores más comunes para la propiedad "type". Hay más tipos disponibles en HTML,
y cada uno tiene un propósito específico para recopilar diferqentes tipos de datos del usuario. Estos otros pueden ser:
**"file", "radio", "input","submit"**, etc. La elección del valor correcto para la propiedad "type" es esencial para
garantizar que los datos ingresados se ajusten adecuadamente al propósito del campo de entrada y que se validen
correctamente antes de enviarlos. Más referencias sobre el tema: https://developer.mozilla.org/es/docs/Learn/Forms

#### 4.Botones tipo `<button>`:

La etiqueta `<button>` en HTML se utiliza para crear botones interactivos dentro de un formulario o en cualquier otra
parte de una página web. Los botones creados con la etiqueta `<button>` pueden tener contenido de texto o incluso
elementos HTML, lo que brinda mayor flexibilidad en su diseño y funcionalidad.

Aquí tienes una descripción de la etiqueta `<button>` y cómo se puede utilizar:

Sintaxis básica:

        <button>Contenido del botón</button>

Características principales:

Contenido del botón: Puedes agregar cualquier tipo de contenido dentro de la etiqueta `<button>`, ya sea texto,
imágenes,
íconos o incluso otros elementos HTML.

Ejemplo con texto:

        <button>Enviar</button>

Ejemplo con ícono:

        <button><i class="fa fa-search"></i> Buscar</button>

**Tipo de botón**: El atributo type se puede utilizar para especificar el tipo de botón. Los valores más comunes son
type="
submit" para enviar un formulario o type="button" para un botón genérico que puede ejecutar una función o acción en
JavaScript.

Ejemplo de botón de envío:

        <button type="submit">Enviar</button>

Ejemplo de botón genérico:

        <button type="button" onclick="saludar()">Saludar</button>

Ejemplo con una clase CSS:

        <button type="button" class="boton-estilizado">Presiona aquí</button>

        <style>
          .boton-estilizado {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
          }
        </style>

La **principal diferencia** entre la etiqueta `<input>` y la etiqueta `<button>` radica en su propósito y funcionalidad
en HTML:

- `<input>`: La etiqueta `<input>` se utiliza principalmente para crear campos de entrada dentro de un formulario. Puede
  tener diferentes tipos, como **type="text"** para campos de texto, **type="checkbox"** para casillas de verificación,
  **type="radio"** para botones de opción, **type="submit"** para botones de envío de formularios, entre otros. Su uso
  principal es permitir a los usuarios ingresar datos o realizar selecciones.

- `<button>`: La etiqueta `<button>` se utiliza para crear botones interactivos en una página web. Pueden tener
  cualquier contenido, como texto, imágenes, íconos o incluso otros elementos HTML. A diferencia de `<input>`, que se
  utiliza principalmente en formularios, `<button>` es más versátil y se puede colocar en cualquier lugar de la página
  para realizar acciones o ejecutar funciones mediante JavaScript.

## LISTAS

En HTML, existen tres etiquetas principales para crear listas: `<ul>`, `<ol>` y `<li>`. Estas etiquetas permiten
organizar y presentar información de manera estructurada y jerárquica. Aquí tienes una descripción de cada una:

- **`<ul>` (Lista desordenada)**:
  La etiqueta `<ul>` se utiliza para crear listas desordenadas, es decir, listas donde los elementos no siguen un orden
  específico. Los elementos de la lista se presentan con viñetas o puntos como marcadores por defecto.

Ejemplo:

        <ul>
          <li>Manzanas</li>
          <li>Naranjas</li>
          <li>Plátanos</li>
        </ul>

**Resultado:**

    - Manzanas
    - Naranjas
    - Plátanos

- **`<ol>` (Lista ordenada)**:
  La etiqueta `<ol>` se utiliza para crear listas ordenadas, es decir, listas donde los elementos siguen un orden
  numérico o alfabético. Los elementos de la lista se presentan con números o letras como marcadores.

Ejemplo:

    <ol>
      <li>Primer elemento</li>
      <li>Segundo elemento</li>
      <li>Tercer elemento</li>
    </ol>

**Resultado:**

    1. Primer elemento
    2. Segundo elemento
    3. Tercer elemento

También dentro de una lista ordenada también podemos indicar el valor por el cuál queremos que empiece nuestra lista.
Esto lo hacemos agregando una propiedad de **value** en la etiqueta, así: `<li value="50">Elemento 1</li>`

Ejemplo:

    <ol>
        <li value="50">Elemento 1</li>
        <li>Elemento 2</li>
        <li>Elemento 3</li>
        <li>Elemento 4</li>
    </ol>

**Resultado:**

    50. Primer elemento
    51. Segundo elemento
    52. Tercer elemento

También se pueden anidar listas dandole un formato de niveles

Ejemplo:

    <ol>
        <li value="50">Elemento 1</li> <!-- value="50" para indicar primer núemero de listsa -->
        <li>Elemento 2</li>
        <li>Elemento 3</li>
        <li>Elemento 4</li>

        <!-- ## Anidar listas en diferentes niveles ##-->

        <li>
            <ol>
                <li>Sub elemento 1</li>
                <li>Sub elemento 2</li>
                <li>Sub elemento 3</li>
            </ol>
        </li>
    </ol>

**Resultado:**

    50. Primer elemento
    51. Segundo elemento
    52. Tercer elemento
    54.   1. Sub elemento 1
          2. Sub elemento 2
          3. Sub elemento 3

Pero esto no se ve muy bien, entonces, también podemos definir un estilo de lista, de la siguiente manera:

    <ol>
        <li value="50">Elemento 1</li> <!-- value="50" para indicar primer núemero de listsa -->
        <li>Elemento 2</li>
        <li>Elemento 3</li>
        <li>Elemento 4</li>
        
        <!-- ## Anidar listas en diferentes niveles ##-->
        <li>
            <ol>
                <!-- ## Con el elemento style, podemos definir otro formato de lista ## -->
                <li style="list-style-type: lower-alpha">Sub elemento 1</li>
                <li style="list-style-type: lower-alpha">Sub elemento 2</li>
                <li style="list-style-type: lower-alpha">Sub elemento 3</li>
            </ol>
        </li>
    </ol>

De esta manera, con el estilo **_style="list-style-type: lower-alpha"_**  logramos otro resultado:

    50. Primer elemento
    51. Segundo elemento
    52. Tercer elemento
    54.   a. Sub elemento 1
          b. Sub elemento 2
          c. Sub elemento 3

- **`<li>` (Elemento de lista)**:
  La etiqueta `<li>` se utiliza para definir cada elemento dentro de una lista (ya sea desordenada o ordenada). Cada
  elemento de la lista debe estar contenido dentro de una etiqueta `<li>`.

Es importante destacar que las etiquetas `<ul>`, `<ol>` y `<li>` son etiquetas de bloque, lo que significa que crean
bloques de contenido que inician en una nueva línea y se extienden horizontalmente hasta el ancho de su contenedor.

Adicionalmente, también existe la etiqueta `<dl>` para crear listas de definición, donde cada término se define junto
con su descripción utilizando las etiquetas `<dt>` y `<dd>`, respectivamente.

Ejemplo de lista de definición:

    <dl>
      <dt>HTML</dt>
      <dd>Lenguaje de marcado utilizado para crear páginas web.</dd>
    
      <dt>CSS</dt>
      <dd>Lenguaje de hojas de estilo utilizado para dar estilo a páginas web.</dd>
    </dl>

## TABLAS

Las tablas en HTML se utilizan para organizar y mostrar datos en una estructura tabular compuesta por filas y columnas.
Las tablas son una herramienta poderosa para presentar información de manera organizada y fácil de leer. Para crear una
tabla en HTML, se utilizan tres etiquetas principales: `<table>`, `<tr>` y `<td>`. Aquí tienes una descripción de cada
una:

- `<table>`: La etiqueta `<table>` se utiliza para crear la tabla en sí misma. Todas las filas y columnas de la tabla
  deben estar contenidas dentro de esta etiqueta.

Ejemplo:

    <table>
      <!-- Filas y columnas irán aquí -->
    </table>

- `<tr>`: La etiqueta `<tr>` se utiliza para definir una fila dentro de la tabla. Todas las celdas de una fila deben
  estar contenidas dentro de esta etiqueta.

Ejemplo:

    <table>
      <tr>
        <!-- Celdas de la primera fila -->
      </tr>
      <tr>
        <!-- Celdas de la segunda fila -->
      </tr>
    </table>

- `<td>`: La etiqueta `<td>` se utiliza para crear una celda de datos dentro de una fila. Cada celda contiene el
  contenido o dato que deseas mostrar en la tabla.

Ejemplo:

    <table>
      <tr>
        <td>Manzanas</td>
        <td>10</td>
      </tr>
      <tr>
        <td>Naranjas</td>
        <td>15</td>
      </tr>
    </table>

Además de `<td>`, también existe la etiqueta `<th>` que se utiliza para crear celdas de encabezado dentro de la tabla.
Las celdas de encabezado son útiles para indicar qué información se muestra en cada columna o fila.

Ejemplo con `<th>`:

    <table>
      <tr>
        <th>Fruta</th>
        <th>Cantidad</th>
      </tr>
      <tr>
        <td>Manzanas</td>
        <td>10</td>
      </tr>
      <tr>
        <td>Naranjas</td>
        <td>15</td>
      </tr>
    </table>

También existen las etiquetas `<thead>`, `<tbody>` y `<tfoot>` que son elementos HTML que se utilizan en conjunto con la
etiqueta `<table>` para dividir y organizar visualmente el contenido de una tabla. Estas etiquetas ayudan a mejorar la
estructura y legibilidad de las tablas, especialmente cuando estas contienen una gran cantidad de datos.

Ejemplo **thead**:

    <table>
      <thead>
        <tr>
          <th>Nombre</th>
          <th>Edad</th>
          <th>País</th>
        </tr>
      </thead>
      <tbody>
        <!-- Filas de datos irán aquí -->
      </tbody>
    </table>

Ejemplo **tbody**:

    <table>
      <thead>
        <tr>
          <th>Nombre</th>
          <th>Edad</th>
          <th>País</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Juan</td>
          <td>30</td>
          <td>España</td>
        </tr>
        <tr>
          <td>María</td>
          <td>25</td>
          <td>México</td>
        </tr>
      </tbody>
    </table>

Ejemplo **tfoot**:

    <table>
      <thead>
        <tr>
          <th>Nombre</th>
          <th>Edad</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Juan</td>
          <td>30</td>
        </tr>
        <tr>
          <td>María</td>
          <td>25</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <td colspan="2">Total de personas: 2</td>
        </tr>
      </tfoot>
    </table>