## Haciendo un menú de barra

En esta tarjeta podrás ver cómo puedes transformar tu menú de navegación en una barra de menú de aspecto fresco, simplemente añadiendo más reglas CSS en la hoja de estilo.

![Ejemplo de una barra de menú](images/egCoolMenuBar.png)

- Ve al archivo de hojas de estilo en la pestaña `styles.css`. Haga clic en ** debajo ** de una llave de cierre `} ` y presione ** Enter ** para crear una nueva línea en blanco. Agregue el siguiente código de CSS:

```css
    nav ul {
        background-color: tomato;
    }
```

¿Te das cuenta de cómo usaste dos selectores en lugar de uno? Si usaste el selector ` ul ` por sí solo, la regla afectaría todas las listas desordenadas en su sitio web. Agregar el selector ` nav ` también hace que solo se aplique a listas que se encuentren entre las etiquetas ` nav `.

![Lista con fondo rojo](images/egMenuBarFirstStyle.png)

Vamos a deshacernos de los puntos de bala. Esos son los puntos delante de cada elemento de la lista.

- Añade el siguiente código CSS al archivo `styles.css`. Otra vez, escribe una nueva linea después del `}` así no estará dentro de ningún otro bloque de reglas.

```css
    nav ul li {
        list-style-type: none;
    }
```

Observe que este conjunto de reglas tiene tres selectores: selecciona todos los elementos ` li ` que están en una lista ` ul ` que está dentro de una sección ` nav `. ¡Uf!

![Lista con puntos de bala eliminados](images/egMenuBarNoBullets.png)

Ahora vamos a hacer la lista horizontal (a través) en lugar de vertical (hacia abajo).

- Dentro de la nueva regla CSS que acabas de crear, agregue la siguiente línea: ` display: inline; ` .

![](images/egMenuBarInline.png)

- Los elementos del menú ahora están todos juntos, así que vamos a agregar las propiedades ` margin-right ` y ` margen-left ` para espaciarlos un poco. El bloque de código CSS debería verse así ahora:

```css
    nav ul li {
        list-style-type: none;
        display: inline;
        margin-right: 10px;
        margin-left: 10px;
    }
```

Recuerde: `10px` significa diez píxeles.

¿Qué te parece hacer que el menú cambie para decirte en qué página estás? Esta parte no estará en la hoja de estilo.

- Comience con la página de inicio. Ve al archivo `index.html`. En la lista de enlaces del menú, elimine las etiquetas de enlace antes y después de la palabra ` Inicio`, de modo que el elemento de la lista para la página de inicio sea solo texto entre `<li> </li>` etiquetas, como esta: `<li> Inicio </li>` .

- Ahora vaya a cada uno de tus otros archivos y haga lo mismo, eliminando las etiquetas de enlace en la página que estás editando. Así que, por ejemplo, en el archivo `music.html` he eliminado las etiquetas de enlace en el elemento de la lista `Música`

```html
    <header>
        <nav>
            <ul>
            <li><a href="index.html">Inicio</a></li>
            <li><a href="attractions.html">Lugares que visitar</a></li>
            <li>Música</li>
            <li><a href="food.html">Comida</a></li>
            </ul>
        </nav>
    </header>
```

- Explore sus páginas haciendo clic en los enlaces. ¿Ver cómo la barra de menú muestra la página en la que estás como texto plano en lugar de un enlace? 

![Ejemplo de barra de menú que resalta la página actual](images/egMenuBarOnPage.png)

En la siguiente tarjeta, aprenderá aún más trucos de CSS para que la barra de menú se vea increíble.