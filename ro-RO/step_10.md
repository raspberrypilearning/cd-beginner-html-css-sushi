## Adăugarea mai multor pagini

Acest card vă va arăta cum să adăugați mai multe pagini pe site-ul dvs. Web.

- În partea de sus a panoului de coduri, faceți clic pe simbolul **+** lângă file și introduceți un nume pentru noul fișier. Trebuie să se termine în `.html` (inclusiv punctul!), Astfel încât browserul să știe că este o pagină web.

![Adăugarea unui nou fișier în Trinket](images/tktNewFileArrows.png)

## \--- colaps \---

## title: Redenumirea sau ștergerea unui fișier

Dacă doriți să modificați numele unui fișier, faceți clic pe pictograma **cog** în partea dreaptă a numelui fișierului, apoi faceți clic pe pictograma **creion**. Introduceți noul nume și apăsați pe **Introduceți**. De asemenea, puteți șterge un fișier făcând clic pe pictograma **bin** în locul pictogramei cu **creion**. ![](images/EditFilename.png)

S-ar putea să vă întrebați de ce nu se poate schimba numele de `index.html` fișier. `index.html` este un nume special folosit pentru **pagina** a unui site web. Aceasta este prima pagină pe care vă aterizați atunci când vizitați un site Web. Ori de câte ori te duci la pagina de pornire a unui site web, browser - ul caută fișierul numit `index.html` și afișează pe ecran.

\--- / colaps \---

- Găsiți fișierul `blank_page.html` și copiați și inserați tot codul din acesta în noul fișier. Deoarece doriți să copiați totul, puteți să faceți clic oriunde pe cod și să utilizați comanda rapidă de la tastatură <kbd>Ctrl</kbd> (sau <kbd>cmd</kbd>) și <kbd>A</kbd> pentru a selecta totul simultan.

- Modificați textul între etichetele `<title> </title>` astfel încât noua dvs. pagină să aibă un titlu adecvat. Trinket nu va afișa titlul, dar îl puteți vedea în partea de sus a ferestrei browserului dacă descărcați proiectul.

![Titlul paginii care apare în fila browser](images/egLocalFileWindowTitle.png)

- Între etichetele `<main> </main>` din noul fișier, utilizați etichetele pe care le-ați învățat despre a adăuga materiale la pagină, cum ar fi paragrafe, titluri, imagini și liste!

- Repetați pașii de mai sus pentru fiecare pagină nouă pe care doriți să o adăugați.

Când există prea multe file pentru ca Trinket să se poată afișa simultan, puteți utiliza pictogramele **<** și **>** din colțul din stânga sus al filelor pentru a derula între ele.

![Butoanele pentru derularea filelor](images/tktScrollTabIcons.png)

Acum trebuie să creați linkuri pentru a putea ajunge la fiecare dintre paginile dvs. noi! Să punem toate legăturile într-o listă.

- În `index.html` fișier, adăugați următorul cod la corpul paginii dvs. Web:

```html
    <ul>
        <li><a href="index.html">Acasă</a></li>
        <li><a href="attractions.html">Locuri de vizitat</a></li>
        <li><a href="music.html">Muzică</a></li>
        <li><a href="food.html">Lucruri de mâncare</a></li>
    </ul>
```

- Modificați valoarea atributului `href` pentru fiecare legătură (amintiți-vă, acesta este textul din ghilimele) astfel încât acesta să se potrivească exact cu numele fiecărui fișier HTML pe care l-ați creat.

- Modificați textul între etichetele `<a> </a>` la descrieri adecvate ale paginilor dvs.

Acum puteți naviga la noile dvs. pagini!

![Listă de exemple de linkuri de pe o pagină Web](images/egListOfPageLinks.png)