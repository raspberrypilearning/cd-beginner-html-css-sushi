## Ajouter une table

Parfois, il peut être utile d'afficher des informations dans une table. Par exemple, vous souhaiterez peut-être répertorier les informations relatives aux membres sur un site Web pour un club de sport ou une école locale, ou des informations sur vos dix chansons favorites.

Une table est une grille composée de **lignes** et **colonnes**. La plupart des tableaux incluent également des titres en haut de chaque colonne, appelés **tête**. Voici un exemple:

![Exemple d'information dans une table](images/egTableResult.png)

- Allez dans le fichier `page_with_table.html`. Là, vous verrez un tas de code entre `<table> </table>` tags.

- Sélectionnez tout le code depuis le début de l'étiquette `<table>` jusqu'à la fin de l'étiquette de fermeture `</table>` et copiez-le. Ensuite, allez dans un de vos fichiers où vous souhaitez mettre une table, et collez le code.

En ce moment votre table est vide.

- Have a go at filling your table with anything you like! Simply put text in between the `<td> </td>` tags and in between the `<th> </th>` tags. You can add more tags if you need them.

## \--- collapse \---

## title: Example code

The HTML code for the table shown above looks like this:

```html
  <table>
    <tr>
      <th>Name of pet</th>
      <th>Animal</th>
      <th>Colour</th>
    </tr>
    <tr>
      <td>Mia</td>
      <td>Cat</td>
      <td>Black and fluffy</td>
    </tr>
    <tr>
      <td>Tito</td>
      <td>Dog</td>
      <td>Black with brown patches</td>
    </tr>
    <tr>
      <td>Honeycomb</td>
      <td>Guinea Pig</td>
      <td>White with orange patches</td>
    </tr>
    <tr>
      <td>Alfie</td>
      <td>Budgie</td>
      <td>Green and yellow</td>
    </tr>
  </table>
```

\--- /collapse \---

To add another **row**, add another set of `<tr> </tr>` tags. In between them, you put the same number of **data** items with `<td> </td>` tags as you have in the other rows.

To add another **column**, add an extra **data** item with a set of `<td> </td>` tags to **every** row. Also add an extra **header** item to the first row, using `<th> </th>` tags.

## \--- collapse \---

## title: How does it work?

Let's have a look at all those tags. It's a bit like the code for a list (remember `<ul>` and `<ol>`) but with more levels.

Each pair of `<tr> </tr>` tags is a row, so everything in between them will be displayed on one line.

The first row contains `<th> </th>` tags. These are used for the headers, so the column titles go in between them. There is one pair for each column you have in your table.

The `<td> </td>` tags define what's called table data, and that's what goes in all the other rows. These are similar to the list item tags `<li> </li>`: everything in between them is one item in your table row.

\--- /collapse \---

- If you look at the end of the `styles.css` file, you will see the CSS code that describes how the table should look. You don't have to understand all of it! But you can experiment with changing the text, border, and background colours to design your own style.

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

Notice how some of the selectors use commas, for example `table, th, td`? That's a **list of selectors**: it means it applies to all `<th>` elements and all `<td>` elements. It saves typing out the same set of rules for each selector!