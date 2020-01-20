## Navegando por tu página web

Muchos sitios web tienen un menú de **navegación** para ayudar a los visitantes a moverse entre las páginas. Ahora que tienes un montón de páginas, una página de inicio y enlaces a cada página, pasemos la lista de enlaces a una sección de navegación en la parte superior de cada página.

![Ejemplo de una página web con enlaces de navegación en la parte superior](images/egNavLinksAtTop.png)

- Encuentra el código para tu lista de enlaces que creaste en el paso anterior.

- Justo antes de la etiqueta `<ul>` de apertura, presiona **Enter** para crear una nueva línea en blanco, luego, en la nueva línea, escribe la siguiente etiqueta: `<nav>`. Trinket agrega automáticamente la etiqueta de cierre justo después, pero puedes eliminarla, si no está en el lugar correcto.

- Solo **después** de la etiqueta `</ul>` de cierre, presiona **Enter** para crear una nueva línea en blanco y escribe la etiqueta `</nav>` de cierre allí.

- Ahora selecciona toda tu sección `<nav>` y la lista, haciendo clic justo antes de la etiqueta `<nav>` de apertura y arrastrando el mouse hasta justo después de la etiqueta `</nav>` de cierre, de modo que todo el texto, incluidas las etiquetas de apertura y cierre estén resaltadas. ¡Asegúrate de que todos **los corchetes angulares** `"<"` y `">"` al principio y al final también están resaltados!

![El texto de la izquierda no está completamente seleccionado mientras que el texto de la derecha lo está](images/egSelectedYayWoops.png)

- Esta vez vas a **cortar** en lugar de copiar. Mantén presionada la tecla <kbd>Ctrl</kbd> (o <kbd>cmd</kbd>) y, mientras la mantienes presionada, presiona la tecla <kbd>X</kbd>. ¡El código resaltado desaparecerá, pero no te asustes!

- En la parte superior del archivo, haz clic en el espacio entre las etiquetas `<header> </header>`. Asegúrate de ver el cursor parpadeando allí. Ahora pega el código presionando <kbd>Ctrl</kbd> (o <kbd>cmd</kbd>) y <kbd>V</kbd>, como de costumbre. El código debería verse así:

```html
    <header>
        <nav>
            <ul>
            <li><a href="index.html">Inicio</a></li>
            <li><a href="attractions.html">Lugares para visitar</a></li>
            <li><a href="music.html">Música</a></li>
            <li><a href="food.html">Cosas para comer</a></li>
            </ul>
        </nav>
    </header>
```

## \--- collapse \---

## title: ¡Deshacer!

Si cometes un error, puedes **deshacerlo** presionando <kbd>Ctrl</kbd> (o <kbd>cmd</kbd>) y <kbd>Z</kbd> a la vez. Por lo general, puedes presionar esta combinación de teclas varias veces para deshacer los últimos cambios. ¡Este es otro atajo de teclado útil que puedes usar en muchos programas!

\--- /collapse \---

- Prueba tus enlaces para asegurarte de que siguen funcionando.

\--- challenge \---

## Desafío: menús de navegación para todas las páginas.

- Coloca esta sección de código en la sección de encabezado de cada archivo HTML que hayas creado. Esto hará que el menú de navegación aparezca en la parte superior de cada página de tu sitio web.
    
    \--- hints \---
    
    \--- hint \---

Select the entire `<nav>` section like you did before, and press the <kbd>Ctrl</kbd> (or <kbd>cmd</kbd>) and <kbd>C</kbd> keys together to copy it.

Then, in each of your `.html` files, click inside the `<header> </header>` section and paste the code exactly like you did earlier.

\--- /hint \---

\--- /hints \---

Now you will be able to click the links no matter which page you are on.

\--- /challenge \---