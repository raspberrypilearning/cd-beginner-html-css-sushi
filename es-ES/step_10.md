## Agregar más páginas

Esta tarjeta le mostrará cómo agregar más páginas a su sitio web.

- En la parte superior del panel de códigos, haga clic en el símbolo **+** junto a las pestañas y escriba un nombre para su nuevo archivo. Debe terminar en `.html` (¡incluido el punto!) Para que el navegador sepa que es una página web.

![Agregar un nuevo archivo en Trinket](images/tktNewFileArrows.png)

## \--- colapso \---

## título: cambio de nombre o eliminación de un archivo

Si desea cambiar el nombre de un archivo, haga clic en el icono **cog** a la derecha del nombre del archivo y luego haga clic en el ícono de **lápices**. Escriba el nuevo nombre y presione **Ingrese**. También puede eliminar un archivo haciendo clic en el icono **bin** lugar del icono **pencil**. ![](images/EditFilename.png)

Es posible que se pregunte por qué no puede cambiar el nombre del archivo `index.html`. `index.html` es un nombre especial utilizado para la página</strong> inicio **** de un sitio web. Esa es la primera página en la que aterrizas cuando visitas un sitio web. Cuando vaya a la página de inicio de un sitio web, el navegador buscará el archivo llamado `index.html` y lo mostrará en su pantalla.

\--- /colapso \---

- Find the file `blank_page.html` and copy and paste all of the code from it into your new file. Since you want to copy the whole thing, you can click anywhere on the code and use the keyboard shortcut <kbd>Ctrl</kbd> (or <kbd>cmd</kbd>) and <kbd>A</kbd> to select all of it at once.

- Change the text in between the `<title> </title>` tags so your new page has a suitable title. Trinket won't display the title, but you can see it at the top of your browser window if you download your project.

![The page title showing in the browser tab](images/egLocalFileWindowTitle.png)

- In between the `<main> </main>` tags in the new file, use the tags you have learned about to add stuff to the page, such as paragraphs, headings, images, and lists!

- Repeat the steps above for each new page that you want to add.

When there are too many tabs for Trinket to show at once, you can use the **<** and **>** icons in the top left-hand corner of the tabs to scroll between them.

![The buttons for scrolling the tabs](images/tktScrollTabIcons.png)

Now you need to make links so that you can get to each of your new pages! Let's put all the links in a list.

- In the `index.html` file, add the following code to the body of your webpage:

```html
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="attractions.html">Places to visit</a></li>
        <li><a href="music.html">Music</a></li>
        <li><a href="food.html">Things to eat</a></li>
    </ul>
```

- Change the value of the `href` attribute for each link (remember, that's the text inside the quotation marks) so that it exactly matches the name of each HTML file that you have created.

- Change the text in between the `<a> </a>` tags to suitable descriptions of your pages.

Now you can navigate to your new pages!

![Example list of links on a web page](images/egListOfPageLinks.png)