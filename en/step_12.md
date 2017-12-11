## Adding a table

- Sometimes it can be useful to show information in a table. For example if you want to list member information on a website for a local sports club or school. Or, in this example, songs!

- A table is a grid made up of **rows** and **columns**. Most tables also include titles at the top of each column, called the **header**.

- Go to the file page\_with\_table.html. There you will see a bunch of code in between `<table> </table>` tags. Select all of the code from the start of the `<table>` tag to the end of the closing `</table>` tag and **copy** it.

- Go to one of your files where you would like to put a table and **paste** in the code.

- Let's have a look at all those tags. It's a bit like the code for a list \(remember `<ul>` and `<ol>`?\) but with more levels.

  Each pair of `<tr> </tr>` tags is a **row**. So everything in between them will be displayed on one line.

  The first row contains `<th> </th>` tags. These are used for the **headers**, so the column titles go in between them. There is one pair for each column you have in your table.

  The `<td> </td>` tags stand for **table data**, and that's what goes in all the other rows. These are like the list item `<li> </li>` tags in a list: everything in between them is one item in your table row.

- Here's an example of a table filled with information
  ```html
    <table>
      <tr>
        <th>Artist</th>
        <th>Song</th>
        <th>Year</th>
      </tr>
      <tr>
        <td>Thin Lizzy</td>
        <td>The Boys Are Back In Town</td>
        <td>1976</td>
      </tr>
      <tr>
        <td>Sinead O'Connor</td>
        <td>Nothing Compares 2 U</td>
        <td>1990</td>
      </tr>
      <tr>
        <td>The Cranberries</td>
        <td>Linger</td>
        <td>1994</td>
      </tr>
    </table>
  ```

- And here's what it looks like on the website 

  ![](images/TableResult2.png)

- Try filling your table with anything you like! Simply put text in between the `<td> </td>` tags and also in between the `<th> </th>` tags. You can add more tags if you need to.

- To add another **row**, you add another set of `<tr> </tr>` tags. In between them you put the same number of **data** items with `<td> </td>` tags as you have in the other rows.

- To add another **column** you add an extra **data** item with a set of `<td> </td>` tags onto every row. You also add an extra **header** item to the first row, using `<th> </th>` tags.

- If you look at the end of the styles.css file, you will see the CSS code that describes how the table should look. You don't have to understand all of it! But you can experiment with changing the text, border and background colours to design your own style.
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

- Notice how some of the selectors use **commas**, for example `table, th, td`? This is a _list of selectors_: it means it applies to _all_ `<th>` elements _and all_ `<td>` elements. It saves typing out the same set of rules again for each selector!