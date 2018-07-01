## Een tabel toevoegen

Soms kan het nuttig zijn om informatie in een tabel weer te geven. Je wilt bijvoorbeeld voor een plaatselijke sportclub of school de ledeninformatie op een website vermelden, of informatie over je top tien favoriete nummers plaatsen.

Een tabel is een raster bestaande uit ** rows ** (rijen) en ** colums ** (kolommen). De meeste tabellen bevatten ook titels bovenaan elke kolom, de **header** (kop). Hier is een voorbeeld:

![Example of information in a table](images/egTableResult.png)

- Ga naar het bestand ` page_with_table.html `. Daar zie je een aantal codes tussen `<table> </table>` tags.

- Selecteer alle code vanaf het begin van de tag `<table>` tot aan het einde van de sluit ` </table>` tag en kopieer het. Ga dan naar een van je bestanden waar je een tabel zou willen plaatsen en plak de code er in.

Op dit moment is je tabel leeg.

- Probeer je tabel te vullen met van alles wat je maar wilt! Simpel gezegd plaats tekst tussen de `<td></td>` tags en tussen de `<th></th>` tags. Als je ze nodig hebt Je kunt meer tags toevoegen.

## \--- collapse \---

## title: Voorbeeldcode

De HTML-code voor de bovenstaande tabel ziet er als volgt uit:

```html
  <table>
    <tr>
      <th>Naam dier</th>
      <th>Dier</th>
      <th>Kleur</th>
    </tr>
    <tr>
      <td>Mia</td>
      <td>Kat</td>
      <td>Zwart</td>
    </tr>
    <tr>
      <td>Tito</td>
      <td>Hond</td>
      <td>Zwart met bruin</td>
    </tr>
    <tr>
      <td>Honeycomb</td>
      <td>Cavia</td>
      <td>Wit met oranje</td>
    </tr>
    <tr>
      <td>Alfie</td>
      <td>grasparkiet</td>
      <td>Groen met geel</td>
    </tr>
  </table>
```

\--- /collapse \---

Om nog een ** rij ** toe te voegen, voeg je nog een set `<tr> </tr>` -tags toe. Daartussen plaatst je hetzelfde aantal ** gegevens ** met `<td> </td>` tags zoals in de andere rijen.

Om nog een **kolom ** toe te voegen, voeg je aan ** elke ** rij extra ** gegevens ** met een set van `<td> </td>` tags toe. Voeg ook een extra ** header ** met `<th> </th>` tags aan de eerste rij toe.

## \--- collapse \---

## title: Hoe werkt het?

Laten we al die tags eens bekijken. Het lijkt een beetje op de code voor een lijst (onthoud `<ul>` en `<ol>`) maar met meer niveaus.

Elk paar `<tr> </tr>` tags is een rij, dus alles daartussen zal op één regel worden weergegeven.

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