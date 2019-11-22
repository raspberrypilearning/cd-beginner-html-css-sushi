## Navegando por su sitio web

Muchos sitios web tienen un **de navegación** menú para ayudar a los visitantes se mueven entre las páginas. Ahora que tiene un montón de páginas, una página de inicio y enlaces a cada página, pasemos la lista de enlaces a una sección de navegación en la parte superior de cada página.

![Ejemplo de una página web con enlaces de navegación en la parte superior](images/egNavLinksAtTop.png)

- Encuentre el código para su lista de enlaces que creó en el paso anterior.

- Justo antes de la etiqueta de apertura `<ul>` , presione **Ingrese** para crear una nueva línea en blanco, luego en la nueva línea escriba la siguiente etiqueta: `<nav>`. Trinket agrega automáticamente la etiqueta de cierre justo después, pero puede eliminarla, no está en el lugar correcto.

- Solo **después de** la etiqueta de cierre `</ul>` , presione **Ingrese** para crear una nueva línea en blanco y escriba la etiqueta de cierre `</nav>` allí.

- Ahora seleccione toda su sección `<nav>` y haga una lista haciendo clic justo antes de la etiqueta de apertura `<nav>` y arrastrando el mouse hasta justo después de la etiqueta de cierre `</nav>` , de modo que todo el texto, incluidas las etiquetas de apertura y cierre se resalta. ¡Asegúrese de que todos los corchetes angulares **** `<` y `>` al inicio y al final también estén resaltados!

![El texto de la izquierda no está completamente seleccionado mientras que el texto de la derecha está](images/egSelectedYayWoops.png)

- Esta vez va a **cortar** lugar de copiar. Mantenga presionada la tecla <kbd>Ctrl</kbd> (o <kbd>cmd</kbd>) y, mientras la mantiene presionada, presione la tecla <kbd>X</kbd>. ¡El código resaltado desaparecerá, pero no se asuste!

- En la parte superior del archivo, haga clic en el espacio entre las etiquetas `<header> </header>`. Asegúrese de ver el cursor parpadeando allí. Ahora pegue el código presionando <kbd>Ctrl</kbd> (o <kbd>cmd</kbd>) y <kbd>V</kbd> como de costumbre. El código debería verse así:

```html
    <header>
        <nav>
            <ul>
            <li><a href="index.html">Hogar</a></li>
            <li><a href="attractions.html">Lugares para visitar</a></li>
            <li><a href="music.html">Música</a></li>
            <li><a href="food.html">Cosas para comer</a></li>
            </ul>
        </nav>
    </header>
```

## \--- collapse \---

## Título: Deshacer!

Si comete un error, puede **deshacer** presionando <kbd>Ctrl</kbd> (o <kbd>cmd</kbd>) y <kbd>Z</kbd> juntos. Por lo general, puede presionar esta combinación de teclas varias veces para deshacer los últimos cambios. ¡Este es otro atajo de teclado útil que puedes usar en muchos programas!

\--- /collapse \---

- Pruebe sus enlaces para asegurarse de que siguen funcionando.

\--- challenge \---

## Desafío: menús de navegación para todas las páginas.

- Coloque esta sección de código en la sección de encabezado de cada archivo HTML que haya creado. Esto hará que el menú de navegación aparezca en la parte superior de cada página de su sitio web.
    
    \--- hints \---
    
    \--- pista \--- Seleccione toda la sección `<nav>` como lo hizo antes, y presione las teclas <kbd>Ctrl</kbd> (o <kbd>cmd</kbd>) y <kbd>C</kbd> juntas para copiarla.

Luego, en cada uno de sus `.html` archivos, haga clic dentro del `<header> </header>` sección y pegar el código exactamente como lo hizo anteriormente. \--- /hint \---

\--- /hints \---

Ahora podrá hacer clic en los enlaces sin importar en qué página se encuentre.

\--- /challenge \---