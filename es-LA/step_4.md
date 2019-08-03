## Controlando cómo se ve

El código que describe como un sitio web se llama **CSS**.

- Mira las pestañas en la parte superior del panel de código, y ve al archivo `styles.css` haciendo clic en la pestaña con ese nombre. El archivo contiene el siguiente texto:

```css
  body {
      background-color: white;
  }
```

- Cambiar el ` blanco ` color a ` LightSkyBlue ` y mira lo que pasa. ¡Tu sitio web debe tener un fondo azul! 

![Example with blue background](images/egFirstCSSbluebg.png)

## \--- collapse \---

## title: ¿Cómo funciona?

Si observas la parte superior del archivo `index.html` verás la siguiente línea:

```html
  <link type="text/css" rel="stylesheet" href="styles.css"/>
```

La línea anterior indica al navegador que busca un archivo especial llamado `styles.css`. Este archivo especial se llama** hojas de estilo**. Puedes reconocer un archivo de hoja de estilo por el `.css` en su nombre.

Una hoja de estilo contiene **reglas** para el cómo debería lucir cada elemento en tu página web.

Las llaves `{ }` y el código entre ellas son un conjunto de ** reglas de CSS ** . La palabra `body (cuerpo)` significa que las reglas son para todos los elementos de `< body>` en tu sitio web. Llamamos al pedacito delante de las llaves como **selector**. Entonces, en este caso, es el selector para los elementos del cuerpo.

Cada regla dentro de las llaves se compone de:

- Una **propiedad ** a la izquierda, seguido de un símbolo de dos puntos `: `
- Un **valor** para la propiedad en el lado derecho después de los dos puntos
- Un símbolo de punto y coma `;` al final

\--- /collapse \---

- Agreguemos reglas para cambiar la apariencia del texto. Agregue dos nuevas líneas dentro de las llaves:

```css
  body {
    background-color: LightSkyBlue;
    font-family: "Helvetica", sans-serif;
    color: purple;
  }
```

Mira cómo esto ha cambiado la página web.

La propiedad `color` siempre es para texto. Aquí, estás configurando el color de todo el texto en el `body` (cuerpo) de tu página web.

- También puede escribir reglas separadas para los encabezados y los párrafos. Para encabezados `<h1>`, utiliza el selector` h1`. Debajo de la llave de cierre que contiene la regla CSS para el cuerpo, agregue el siguiente código.

```css
  h1 {
    color: orange;
    font-family: "Times New Roman", serif;
  }
```

El texto del encabezado debe ser anaranjado ahora, con el párrafo en morado como antes.

![Result of new CSS code](images/egCssColorsFonts.png)

¿Te das cuenta de que las letras también se ven diferentes además de tener un color diferente? Esto se debe a que cambiaste su **font family** (familia tipográfica). Puedes encontrar algunas fuentes más [ aquí ](http://dojo.soy/web-font-families) .

- Intenta agregar un conjunto de reglas para los encabezados `<h2>`, utilizando el selector` h2 `.

- ¿Por qué no experimentar con diferentes combinaciones de colores para el texto y el fondo? Hay muchos colores disponibles para usar. Encuentre una lista completa de ellos [ aquí ](http://dojo.soy/web-color-names).