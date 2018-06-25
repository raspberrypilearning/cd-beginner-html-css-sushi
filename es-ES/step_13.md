## Diseñando la barra de menú

Con CSS, las posibilidades para que tu barra de menú se vea genial son infinitas.

- Vuelva al archivo `styles.css` - ¡el lugar donde sucede lo genial!

- Busque su selector `nav ul` y agregue más reglas para que se vea así:

```css
  nav ul {background-color: tomato; border-style: sólido; border-color: MediumVioletRed; ancho del borde: 2px; relleno: 10px; }
```

La propiedad `relleno` agrega espacio. ¿Puedes averiguar qué hacen cada una de las otras propiedades? Intente experimentar con diferentes colores y números de píxeles.

![Barra de menú con bordes y relleno añadidos](images/egMenuBarMoreStyle.png)

- Para deshacerse del subrayado de los enlaces, agregue el siguiente código en una nueva línea después de cerrar el corchete `}` para las `reglas de nav ul li`. Podrías ponerlo después de cualquier `}`, pero es una buena idea mantener las cosas relacionadas juntas para que sea más fácil de encontrar.

```css
  nav ul li a {text-decoration: none; }
```

La regla anterior se aplica a los enlaces `<a>` dentro de los elementos de la lista `<li>` en una lista desordenada `<ul>` dentro de una sección de navegación `<nav>`. ¡Guau, son cuatro selectores!

![Barra de menús con el enlace subrayando eliminado](images/egMenuBarNoUnderline.png)

¿Recuerda cómo eliminó las etiquetas de enlace de algunos elementos de la lista en el `<nav>` para que pueda ver fácilmente en qué página se encuentra? ¿Por qué no cambiar también el color del texto de los elementos de la lista de navegación que no son enlaces?

- Busque su selector `nav ul li` y **dentro de** las llaves agreguen la línea:

```css
  color: PapayaWhip;
```

¡Puedes elegir el color que quieras!

También puede agregar la propiedad `color` a la regla `nav ul li a` si desea que los enlaces del menú tengan un color diferente al de otros enlaces en su sitio web.

- ¿Qué tal unas esquinas redondeadas para su menú? Intente agregar el siguiente código a la regla `nav ul` para ver qué sucede: `border-radius: 10px;`.

La propiedad `border-radius` es una manera realmente fácil de hacer que todo parezca más fresco.

![Página web con esquinas redondeadas en la barra de menú y en una imagen](images/egMenuBarFullStyles_result.png)

\--- desafío \---

## Desafío: haz que tus imágenes tengan esquinas redondeadas

- En su hoja de estilo, crear un nuevo conjunto de reglas para las imágenes utilizando el `img` selector, y añadir en un `la frontera de radio` regla allí.

\--- / desafío \---