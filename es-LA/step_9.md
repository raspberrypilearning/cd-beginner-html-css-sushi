## Agregando más paginas

Esta tarjeta te mostrará como agregar más páginas a tu sitio web.

- En la parte de arriba del Panel de Código, haz click en el símbolo **+** a un lado de las pestañas, y escribe un nombre para tu nuevo archivo. Debe de terminar con `.html` (incluyendo el punto!) para que el navegador reconozca que es una página web.

![Añadiendo un nuevo archivo en Trinket](images/tktNewFileArrows.png)

## \--- collapse \---

## title: Renombrando o borrando un archivo

Si quieres cambiar el nombre de un archivo, da clic en el ícono **cog** a la derecha del nombre del archivo, y luego da click en el ícono de **pencil**. Escribe el nuevo nombre y presiona **Enter**. Tu también puedes borrar un archivo solamente dando clic en el icono **bin** en lugar del icono del **pencil**.

![](images/EditFilename.png)

Tal vez te preguntes por qué no puedes cambiar el nombre del archivo `index.html`. `index.html` es un nombre especial usado para la **homepage** del sitio web. Esa es la primera página a la que llegas cuando visitas un sitio web. Cuando vas a la página de inicio de un sitio web, el navegador busca el archivo `index.html` y lo muestra en tu pantalla.

\--- /collapse \---

- Encuentra el archivo `blank_page.html`, copia y pega todo el código en tu nuevo archivo. Ya que quieres copiar todo, tu puedes dar clic en cualquier parte del código y usar el atajo del teclado <kbd>Ctrl</kbd> (or <kbd>cmd</kbd>) y<kbd>A</kbd> para seleccionar todo de una sola vez.

- Cambia el texto entre `<title> </title>` tags para que tu nueva página web tenga el título adecuado. Trinket no mostrará el título, pero puedes verlo en la parte superior de la ventana de tu navegador si tu descargas el proyecto.

![El título de la página que se muestra en la pestaña del navegador](images/egLocalFileWindowTitle.png)

- Entre las `<main> </main>` etiquetas en el nuevo archivo, usa las etiquetas que has aprendido para agregar elementos a la página, como párrafos, encabezados, imágenes y listas!

- Repite los pasos anteriores para cada página nueva que desees agregar.

Cuando hay demasiadas pestañas para que Trinket las muestre a la vez, puedes usar los iconos **<** y **>** en la esquina superior izquierda de las pestañas para desplazarte entre ellas.

![Los botones para desplazar las pestañas](images/tktScrollTabIcons.png)

¡Ahora necesitas crear enlaces para poder acceder a cada una de tus nuevas páginas! Vamos a poner todos los enlaces en una lista.

- En el archivo `index.html`, agrega el siguiente código al cuerpo de tu página web:

```html
    <ul>
        <li><a href="index.html">Inicio</a></li>
        <li><a href="attractions.html">Lugares para Visitar</a></li>
        <li><a href="music.html">Música</a></li>
        <li><a href="food.html">Cosas para comer</a></li>
    </ul>
```

- Cambia el valor del atributo ` href ` para cada enlace (recuerda, ese es el texto entre comillas) para que coincida exactamente con el nombre de cada archivo HTML que hayas creado.

- Cambia el texto entre las etiquetas `<a> </a>` por las descripciones adecuadas de tus páginas.

¡Ahora puedes navegar por tus nuevas páginas!

![Ejemplo de lista de enlaces en una página web](images/egListOfPageLinks.png)