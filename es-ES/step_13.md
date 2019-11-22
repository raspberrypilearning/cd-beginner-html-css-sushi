## Agregar una mesa

A veces puede ser útil mostrar información en una tabla. Por ejemplo, es posible que desee incluir información sobre los miembros en un sitio web de un club deportivo o escuela local, o información sobre sus diez canciones favoritas.

Una tabla es una cuadrícula formada por **filas** y **columnas**. La mayoría de las tablas también incluyen títulos en la parte superior de cada columna, llamados **encabezado**. Aquí está un ejemplo:

![Ejemplo de información en una tabla.](images/egTableResult.png)

- Vaya al archivo `page_with_table.html`. Allí verá un montón de código entre `<table> </table>` etiquetas.

- Seleccione todo el código desde el comienzo de la etiqueta `<table>` hasta el final de la etiqueta de cierre `</table>` y cópielo. Luego vaya a uno de sus archivos donde le gustaría poner una tabla y pegue el código.

En este momento tu mesa está vacía.

- ¡Intenta llenar tu mesa con lo que quieras! Simplemente coloque texto entre las etiquetas `<td> </td>` y entre las etiquetas `<th> </th>`. Puede agregar más etiquetas si las necesita.

## \--- collapse \---

## título: código de ejemplo

El código HTML para la tabla que se muestra arriba se ve así:

```html
  <table>
    <tr>
      <th>Nombre de la mascota</th>
      <th>Animal</th>
      <th>Color</th>
    </tr>
    <tr>
      <td>Mia</td>
      <td>Gato</td>
      <td>Negro y esponjoso</td>
    </tr>
    <tr>
      <td>Tito</td>
      <td>Perro</td>
      <td>Negro con parches marrones</td>
    </tr>
    <tr>
      <td>Panal</td>
      <td>Conejillo de Indias</td>
      <td>Blanco con parches naranjas</td>
    </tr>
    <tr>
      <td>Alfie</td>
      <td>Budgie</td>
      <td>Verde y amarillo</td>
    </tr>
  </table>
```

\--- /colapsar \---

Para agregar otra **fila**, agregue otro conjunto de etiquetas `<tr> </tr>`. Entre ellos, coloca el mismo número de **datos** con etiquetas `<td> </td>` que tiene en las otras filas.

Para agregar otra **columna**, agregue un elemento adicional de **datos** con un conjunto de `<td> </td>` etiquetas a **cada** filas. Agregue también un elemento adicional de **encabezado** a la primera fila, usando `<th> </th>` etiquetas.

## \--- collapse \---

## title: ¿Cómo funciona?

Echemos un vistazo a todas esas etiquetas. Es un poco como el código de una lista (recuerde `<ul>` y `<ol>`) pero con más niveles.

Cada par de etiquetas `<tr> </tr>` es una fila, por lo que todo lo que se encuentre entre ellas se mostrará en una línea.

La primera fila contiene `<th> </th>` etiquetas. Estos se utilizan para los encabezados, por lo que los títulos de las columnas van entre ellos. Hay un par para cada columna que tiene en su tabla.

Las etiquetas `<td> </td>` definen lo que se llama datos de tabla, y eso es lo que pasa en todas las otras filas. Son similares a las etiquetas de elementos de la lista `<li> </li>`: todo lo que hay entre ellas es un elemento en la fila de la tabla.

\--- /collapse \---

- Si observa el final del archivo `styles.css` , verá el código CSS que describe cómo debería verse la tabla. ¡No tienes que entenderlo todo! Pero puede experimentar cambiando el texto, el borde y los colores de fondo para diseñar su propio estilo.

```css
  table, th, td {
    borde: 1px HoneyDew sólido;
    colapso del borde: colapso;
  }
  tr {
    color de fondo: turquesa pálido;
  }
  th, td {
    vertical-align: top;
    acolchado: 5px;
    alineación 
 texto: izquierda;
  }
  th {
    color: morado;
  }
  td {
    color: púrpura;
}
```

Observe cómo algunos de los selectores usan comas, por ejemplo, `table, th, td`? Esa es una lista **de selectores**: significa que se aplica a todos los elementos `<th>` y todos los elementos `<td>`. ¡Ahorra escribir el mismo conjunto de reglas para cada selector!