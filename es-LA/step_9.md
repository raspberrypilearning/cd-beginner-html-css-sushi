## Agregando más paginas

Esta tarjeta te mostrará como agregar mas páginas a tu sitio web.

- En parte de arriba del Panel de Código, haz click en el símbolo **+** a un lado de las pestañas, y escribe un nombre para tu nuevo archivo. Debe de terminar con `.html` (incluyendo el punto!) para que el navegador reconozca que es una página web.

![Añadiendo un nuevo archivo en Trinket](images/tktNewFileArrows.png)

## \--- collapse \---

## title: Renombrando o borrando un archivo

Si tu quieres cambiar el nombre de un archivo, da clik en el ícono **cog** a la derecha del nombre del archivo, y luego da click en ícono de **pencil**. Escribe el nuevo nombre y presiona **Enter**. Tu tambien puedes borrar un archivo solamente dando click en el ícono **bin** en lugar del ícono del **pencil**. ![](images/EditFilename.png)

Tu te podrias estar preguntando porque no puedes cambiar el nombre de archivo `index.html`. `index.html` es un nombre especial usado para la **homepage** del sitio web. Esa es la primer página que se desplegará cuando tu visites tu sitio web. Cada vez que vas a la página principal de tu sitio web, el navegador buscará un archivo llamado `index.html` y aparecerá desplegado en tu monitor.

\--- /collapse \---

- Encuentra el archivo `blank_page.html`, copia y pega todo el código en tu nuevo archivo. Ya que quieres copiar todo, tu puedes dar click en cualquier parte del código y usar el atajo del teclado <kbd>Ctrl</kbd> (or <kbd>cmd</kbd>) y<kbd>A</kbd> para seleccionar todo de una sola vez.

- Cambia el texto entre `<title> </title>` tags para que tu nueva pagina web tenga el título adecuado. Trinket no mostrará el título, pero puedes verlo en la parte superior de la ventana de tu navegador si tu descargas el proyecto.

![El título de la página que se muestra en la pestaña del navegador](images/egLocalFileWindowTitle.png)

- Entre las `<main> </main>` etiquetas en el nuevo archivo, use las etiquetas que has aprendido para agregar elementos a la página, como párrafos, encabezados, imágenes y listas!

- Repite los pasos anteriores para cada página nueva que desees agregar.

Cuando hay demasiadas pestañas para que Trinket se muestre a la vez, tu puedes usar los íconos **<** y **>** en la esquina superior izquierda de las pestañas para desplazarte entre ellas.

![Los botones para desplazar las pestañas](images/tktScrollTabIcons.png)

Ahora necesitas crear enlaces para poder acceder a cada una de sus nuevas páginas! Vamos a poner todos los enlaces en una lista.

- En el archivo `index.html`, agrega el siguiente código al cuerpo de su página web:

```html
    <ul>
        <li><a href="index.html">Principal</a></li>
        <li><a href="attractions.html">Lugares que Visitar</a></li>
        <li><a href="music.html">Música</a></li>
        <li><a href="food.html">Comidas</a></li>
    </ul>
```

- Cambia el valor del atributo ` href ` para cada enlace (recuerda, ese es el texto entre comillas) para que coincida exactamente con el nombre de cada archivo HTML que hayas creado.

- Cambia el texto entre las etiquetas `<a> </a>` por las descripciones adecuadas de tus páginas.

Ahora puedes navegar a tus nuevas páginas!

![Ejemplo de lista de enlaces en una página web](images/egListOfPageLinks.png)