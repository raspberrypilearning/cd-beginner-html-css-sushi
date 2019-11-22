## Dando estilo a la barra de menú

Con CSS, las posibilidades de hacer que su barra de menú se vea genial son infinitas.

- Vuelva al archivo `styles.css` nuevamente, ¡el lugar donde ocurren las cosas geniales!

- Encuentre su selector `nav ul` y agregue más reglas para que se vea así:

```css
  nav ul {
    color de fondo: tomate;
    estilo de borde: sólido;
    color de borde: MediumVioletRed;
    ancho de borde: 2px;
    relleno: 10px;
}
```

La propiedad `padding` agrega espacio. ¿Puedes resolver lo que hacen las otras propiedades? Intenta experimentar con diferentes colores y números de píxeles.

![Barra de menú con bordes y relleno añadidos](images/egMenuBarMoreStyle.png)

- Para deshacerse del subrayado de los enlaces, agregue el siguiente código en una nueva línea después del cierre de llaves `}` para las `reglas de navegación ul ul`. Puede ponerlo después de cualquier `}`, pero es una buena idea mantener juntas las cosas relacionadas para que sea más fácil de encontrar.

```css
  nav ul li a {
      text-decoration: none;
}
```

La regla anterior se aplica a los enlaces `<a>` dentro de los elementos de la lista `<li>` en una lista desordenada `<ul>` dentro de una sección de navegación `<nav>`. ¡Vaya, son cuatro selectores!

![Barra de menú con enlace subrayado eliminado](images/egMenuBarNoUnderline.png)

¿Recuerda cómo eliminó las etiquetas de enlace de algunos elementos de la lista en el `<nav>` para que pueda ver fácilmente en qué página se encuentra? ¡Por qué no cambiar también el color del texto de esos elementos de la lista de navegación que no son enlaces!

- Encuentra tu `nav ul li` selector, y **dentro de** las llaves agregan la línea:

```css
  color: PapayaWhip;
```

¡Puedes elegir el color que quieras!

También puede agregar la propiedad `color` a la regla `nav ul li a` si desea que los enlaces del menú sean de un color diferente al de otros enlaces en su sitio web.

- ¿Qué tal algunas esquinas redondeadas para su menú? Intente agregar el siguiente código a la regla `nav ul` para ver qué sucede: `border-radius: 10px;`

¡La propiedad `border-radius` es una manera realmente fácil de hacer que todo se vea mejor!

![Página web con esquinas redondeadas en la barra de menú y en una imagen](images/egMenuBarFullStyles_result.png)

\--- desafío \---

## Desafío: haga que sus imágenes tengan esquinas redondeadas

- En su hoja de estilo, cree un nuevo conjunto de reglas para imágenes usando el selector `img` , y agregue allí una regla de `bordes-radio`.

\--- /challenge \---