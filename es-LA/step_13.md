## Agregando una tabla

A veces puede ser útil mostrar información en una tabla. Por ejemplo, es posible que desees incluir información sobre los miembros en un sitio web de un club deportivo local o escuela, o información sobre tus diez canciones favoritas.

Una tabla es una cuadrícula compuesta de ** filas ** y ** columnas **. La mayoría de las tablas también incluyen títulos en la parte superior de cada columna, llamados **encabezado**. Aquí está un ejemplo:

![Ejemplo de información en una tabla.](images/egTableResult.png)

- Ve al archivo ` page_with_table.html `. Allí verá un montón de código entre etiquetas `<table> </table>`.

- Seleccione todo el código desde el comienzo de la etiqueta `<table>` hasta el final de la etiqueta de cierre ` </table>` y copialo. Luego ve a uno de tus archivos donde te gustaría poner una tabla y peguelo en el código.

En este momento su tabla está vacía.

- ¡Intenta llenar tu tabla con lo que quieras! Simplemente ponga texto entre `<td> </td>` etiquetas y entre las etiquetas `<th> </th>`. Puedes añadir más etiquetas si las necesitas.

## \--- collapse \---

## title: código de ejemplo

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
      <td>Negro con manchas marrones</td>
    </tr>
    <tr>
      <td>Hamtaro</td>
      <td>Cuy</td>
      <td>Blanco con manchas anaranjadas</td>
    </tr>
    <tr>
      <td>Alfie</td>
      <td>Periquito</td>
      <td>Verde y amarillo</td>
    </tr>
  </table>
```

\--- /collapse \---

Para agregar otra **fila**, añade otro conjunto de etiquetas `<tr> </tr>`. Entre ellos, pon el mismo número de elementos ** datos ** con etiquetas `<td> </td>` como las que tienes en las otras filas.

Para agregar otra **columna **, agregue **datos ** adicionales y elementos con un conjunto de etiquetas `<td> </td>` a ** cada ** fila. Agregue también un ** encabezado** adicional a la primera fila, usando etiquetas `<th> </th>`.

## \--- collapse \---

## title: ¿Cómo funciona?

Echemos un vistazo a todas esas etiquetas. Es un poco como el código de una lista (recuerde `<ul>` y `<ol>`) pero con más niveles.

Cada par de etiquetas `<tr> </tr>` son una fila, por lo que todo lo que se encuentre entre ellas se mostrará en una línea.

La primera fila contiene etiquetas `<th> </th>`. Estos se utilizan para los encabezados, por lo que los títulos de las columnas van entre ellos. Hay un par para cada columna que tienes en tu tabla.

Las etiquetas `<td> </td>` definen como serán llamados los datos de la tabla y lo que ocurrirá en todas las otras filas. Son similares a las etiquetas de elementos de la lista `<li> </li>`: todo lo que hay entre ellos es un elemento en la fila de la tabla.

\--- /collapse \---

- Si observas el final del archivo `styles.css` verás el código CSS que describe cómo lucirá la tabla. ¡No tienes que entender todo! Pero puede experimentar cambiando el texto, el borde y los colores de fondo para diseñar su propio estilo.

```css
  table, th, td {
    border: 1px solid HoneyDew;
    border-collapse: collapse;
  }
  tr {
    background-color: PaleTurquoise;
  }
  th, td {
    vertical-align: top;
    padding: 5px;
    text-align: left;
  }
  th {
    color: purple;
  }
  td {
    color: purple;
  }
```

Observas cómo algunos de los selectores usan comas, por ejemplo ` table, th, td `? Esa es una **lista de selectores**: significa que se aplica a todos los elementos `<th>` y todos los elementos `<td>`. ¡Guarda el mismo conjunto de reglas para cada selector!