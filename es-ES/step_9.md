## Añadiendo más páginas

Esta tarjeta te mostrará cómo agregar más páginas a tu sitio web.

- En la parte superior del panel de códigos, haz clic en el símbolo **+** junto a las pestañas y escribe un nombre para tu nuevo archivo. Debe terminar en `.html` (¡incluido el punto!) Para que el navegador sepa que es una página web.

![Agregar un nuevo archivo en Trinket](images/tktNewFileArrows.png)

## \--- collapse \---

## title: Cambiar el nombre o eliminar un archivo

Si deseas cambiar el nombre de un archivo, haz clic en el icono del **engranaje** a la derecha del nombre del archivo y luego haga clic en el icono **lápiz**. Escribe el nuevo nombre y presiona **Enter**. También puedes eliminar un archivo haciendo clic en el icono de la **papelera** en lugar del icono del **lápiz**.

![](images/EditFilename.png)

You might be wondering why you can't change the name of the `index.html` file. `index.html` is a special name used for the **homepage** of a website. That's the first page you land on when you visit a website. Whenever you go to a website's homepage, the browser looks for the file called `index.html` and displays it on your screen.

\--- /collapse \---

- Busca el archivo `blank_page.html` y copia y pega todo el código de él en tu nuevo archivo. Como quieres copiarlo todo, puedes hacer clic en cualquier parte del código y usar el método abreviado de teclado <kbd>Ctrl</kbd> (o <kbd>cmd</kbd>) y <kbd>A</kbd> para seleccionarlo todo de una vez.

- Cambia el texto entre las etiquetas `<title> </title>` para que tu nueva página tenga un título adecuado. Trinket no mostrará el título, pero puedes verlo en la parte superior de la ventana de tu navegador si descargas tu proyecto.

![The page title showing in the browser tab](images/egLocalFileWindowTitle.png)

- Entre las etiquetas `<main> </main>` en el nuevo archivo, usa las etiquetas que has aprendido para agregar cosas a la página, como ¡párrafos, encabezados, imágenes y listas!

- Repite los pasos anteriores para cada nueva página que desees agregar.

When there are too many tabs for Trinket to show at once, you can use the **<** and **>** icons in the top left-hand corner of the tabs to scroll between them.

![The buttons for scrolling the tabs](images/tktScrollTabIcons.png)

Now you need to make links so that you can get to each of your new pages! Let's put all the links in a list.

- En el archivo `index.html`, agrega el siguiente código al cuerpo (body) de tu página web:

```html
    <ul>
        <li><a href="index.html">Inicio</a></li>
        <li><a href="attractions.html">Lugares para visitar</a></li>
        <li><a href="music.html">Música</a></li>
        <li><a href="food.html">Cosas para comer</a></li>
    </ul>
```

- Cambia el valor del atributo `href` para cada enlace (recuerda, es el texto dentro de las comillas) para que coincida exactamente con el nombre de cada archivo HTML que hayas creado.

- Cambia el texto entre las etiquetas `<a> </a>` por descripciones adecuadas de tus páginas.

Now you can navigate to your new pages!

![Example list of links on a web page](images/egListOfPageLinks.png)