## Adăugarea unui tabel

Uneori poate fi utilă afișarea informațiilor într-un tabel. De exemplu, ați putea dori să enumerați informațiile despre membri pe un site web pentru un club sportiv local sau o școală sau informații despre primele zece melodii preferate.

Un tabel este o rețea formată din **rânduri** și **coloane**. Cele mai multe tabele includ , de asemenea titluri din partea de sus a fiecărei coloane, numit **antet**. Iată un exemplu:

![Exemplu de informații într-un tabel](images/egTableResult.png)

- Accesați fișierul `page_with_table.html`. Acolo veți vedea o grămadă de cod între `<table> </table>` tag-uri.

- Selectați tot codul de la începutul etichetei `<table>` până la sfârșitul etichetei de încheiere `</table>` și copiați-l. Apoi, mergeți la unul dintre fișierele în care doriți să puneți o masă și să inserați codul.

În momentul în care masa dvs. este goală.

- Mergi la completarea mesei cu tot ce îți place! Purtați simplu text între etichetele `<td> </td>` și între etichetele `<th> </th>`. Puteți adăuga mai multe etichete dacă aveți nevoie de ele.

## \--- colaps \---

## titlu: cod exemplu

Codul HTML pentru tabelul de mai sus arată astfel:

```html
  <table>
    <tr>
      <th>Numele animalului de companie</th>
      <th>Animale</th>
      <th>Culoare</th>
    </tr>
    <tr>
      <td>Mia</td>
      <td>Cat</td>
      <td>Negru și pufos</td>
    </tr>
    <tr>
      <td>Tito</td>
      <td>Câine</td>
      <td>Negru cu patch-uri maro</td>
    </tr>
    <tr>
      <td>Fagure de miere</td>
      <td>Cobai</td>
      <td>Alb cu patch-uri portocalii</td>
    </tr>
    <tr>
      <td>Alfie</td>
      <td>Budgie</td>
      <td>Verde și galben</td>
    </tr>
  </table>
```

\--- / colaps \---

Pentru a adăuga încă **rândul**, adăugați un alt set de etichete `<tr> </tr>`. Între ele, puneți același număr de date **date** cu `<td> </td>` etichete pe care le aveți în celelalte rânduri.

Pentru a adăuga un alt **coloană**, se adaugă un plus de **date** articol cu un set de `<td> </td>` etichete la **la fiecare** rând. Adăugați, de asemenea, un extra **antet** element la primul rând, utilizând `<th> </th>` etichete.

## \--- colaps \---

## titlu: Cum funcționează?

Să aruncăm o privire la toate etichetele. Este un pic ca un cod pentru o listă (amintiți-vă `<ul>` și `<ol>`), dar cu mai multe nivele.

Fiecare pereche de etichete `<tr> </tr>` este un rând, astfel încât totul între ele va fi afișat pe o singură linie.

Primul rând conține `<th> </th>` etichete. Acestea sunt folosite pentru anteturi, deci titlurile coloanelor intră între ele. Există o pereche pentru fiecare coloană pe care o aveți în tabelul dvs.

Etichetele `<td> </td>` definesc ceea ce se numește date de tabel, și asta se întâmplă în toate celelalte rânduri. Acestea sunt similare cu tag-urile item list `<li> </li>`: totul între ele este un element în rândul tău de tabel.

\--- / colaps \---

- Dacă te uiți la sfârșitul fișierului `styles.css` , vei vedea codul CSS care descrie cum ar trebui să arate tabelul. Nu trebuie să înțelegi totul! Dar puteți experimenta modificarea culorilor de text, de frontieră și de fundal pentru a vă crea propriul stil.

```css
  tabel, th, td {border: 1px solid HoneyDew; colaps de frontieră: colaps; } tr {fundal-culoare: PaleTurquoise; } th, td {vertical-align: top; padding: 5px; text-aliniere: stânga; } th {culoare: violet; } td {culoare: mov; }
```

Observați cum unora dintre selectori se folosesc virgule, de exemplu `tabel, th, td`? Aceasta este o listă **de selectori**: înseamnă că se aplică tuturor celor `<th>` elemente și tuturor celor `<td>` elemente. Salvează tastarea aceluiași set de reguli pentru fiecare selector!