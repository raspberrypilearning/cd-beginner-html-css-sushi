## Hinzufügen einer Tabelle

Manchmal kann es nützlich sein, Informationen in einer Tabelle anzuzeigen. Zum Beispiel möchten Sie vielleicht Mitgliederinformationen auf einer Website für einen örtlichen Sportverein oder eine Schule oder Informationen über Ihre Top-Ten-Lieblingslieder auflisten.

Eine Tabelle ist ein Raster, das aus **Zeilen** und **Spalten**. Die meisten Tabellen enthalten auch Titel am Anfang jeder Spalte, die als **Header**. Hier ist ein Beispiel:

![Beispiel für Informationen in einer Tabelle](images/egTableResult.png)

- Gehe zur Datei `page_with_table.html`. Dort sehen Sie eine Menge Code zwischen `<table> </table>` Tags.

- Wählen Sie den gesamten Code vom Anfang des `<table>` -Tags bis zum Ende des schließenden `</table>` -Tags und kopieren Sie ihn. Gehen Sie dann zu einer Ihrer Dateien, in die Sie eine Tabelle einfügen möchten, und fügen Sie den Code ein.

Im Moment ist dein Tisch leer.

- Versuchen Sie, Ihren Tisch mit allem zu füllen, was Sie mögen! Einfach Text zwischen den `<td> </td>` Tags und zwischen den `<th> </th>` Tags einfügen. Sie können weitere Tags hinzufügen, wenn Sie sie benötigen.

## \--- Einsturz \---

## Titel: Beispielcode

Der HTML-Code für die oben gezeigte Tabelle sieht folgendermaßen aus:

```html
  <table>
    <tr>
      <th>Name des Haustieres</th>
      <th>Tier</th>
      <th>Farbe</th>
    </tr>
    <tr>
      <td>Mia</td>
      <td>Katze</td>
      <td>Schwarz und flauschig</td>
    </tr>
    <tr>
      <td>Tito</td>
      <td>Hund</td>
      <td>Schwarz mit braunen Flecken</td>
    </tr>
    <tr>
      <td>Waben</td>
      <td>Meerschweinchen</td>
      <td>Weiß mit orangen Flecken</td>
    </tr>
    <tr>
      <td>Alfie</td>
      <td>Wellensittich</td>
      <td>Grün und Gelb</td>
    </tr>
  </table>
```

\--- / einklappen \---

Fügen Sie einen weiteren Satz von `<tr> </tr>` -Tags hinzu, um eine weitere **Zeile**hinzuzufügen. Zwischen ihnen setzen Sie die gleiche Anzahl von **Daten** Elemente mit `<td> </td>` Tags, wie Sie in den anderen Zeilen haben.

Um eine weitere **Spalte**hinzuzufügen, fügen Sie ein zusätzliches **Daten-** Element mit einem Satz von `<td> </td>` Tags zu **alle** Zeilen hinzu. Fügen Sie außerdem ein zusätzliches **Header-** Element zur ersten Zeile hinzu, indem Sie `<th> </th>` -Tags verwenden.

## \--- Einsturz \---

## Titel: Wie funktioniert es?

Sehen wir uns all diese Tags an. Es ist ein bisschen wie der Code für eine Liste (erinnere dich an `<ul>` und `<ol>`), aber mit mehr Ebenen.

Jedes Paar von `<tr> </tr>` -Tags ist eine Zeile, so dass alles dazwischen in einer Zeile angezeigt wird.

Die erste Zeile enthält `<th> </th>` Tags. Diese werden für die Header verwendet, sodass die Spaltentitel zwischen ihnen liegen. Es gibt ein Paar für jede Spalte, die Sie in Ihrer Tabelle haben.

Die `<td> </td>` -Tags definieren sogenannte Tabellendaten, und das gilt auch für alle anderen Zeilen. Diese ähneln den Listenelement-Tags `<li> </li>`: Alles dazwischen ist ein Element in Ihrer Tabellenzeile.

\--- / einklappen \---

- Wenn Sie das Ende der Datei `styles.css` , sehen Sie den CSS-Code, der beschreibt, wie die Tabelle aussehen sollte. Sie müssen nicht alles verstehen! Sie können jedoch experimentieren, indem Sie die Text-, Rahmen- und Hintergrundfarben ändern, um Ihren eigenen Stil zu entwerfen.

```css
  Tabelle, th, td {Grenze: 1px fest HoneyDew; Grenzkollaps: Kollaps; } tr {Hintergrundfarbe: PaleTurquoise; } th, td {vertikal ausrichten: oben; Auffüllen: 5px; Textausrichtung: links; } th {Farbe: lila; } td {Farbe: lila; }
```

Beachten Sie, wie einige der Selektoren Kommas verwenden, zum Beispiel `Tabelle, th, td`? Das ist eine **Liste von Selektoren**: das heißt, sie gilt für alle `<th>` Elemente und alle `<td>` Elemente. Es spart das gleiche Regelwerk für jeden Selektor!