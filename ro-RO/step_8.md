## Efectuarea unei liste

Acum veți învăța cum să transformați o listă de articole, cum ar fi "unicorns, roboți, pisici", într-o listă cu aspect frumos, pe care o puteți face mai târziu.

- În `index.html` fișier, adăugați următorul cod chiar deasupra liniei cu `</main>` pe ea:

```html
    <ul>
        <li>Vaci</li>
        <li>Oi</li>
        <li>Lupi</li>
        <li>Lilieci</li>
    </ul>
```

Rezultatul ar trebui să fie o listă plăcută:

![Lista neordonata](images/egUnorderedList.png)

Observați că există o pereche separată de taguri `<li> </li>` jurul fiecărui element din listă.

Aceasta este o listă a unor animale pe care le-ați putea vedea în Irlanda. Puteți modifica elementele din listă la lucruri care au sens pentru site-ul dvs. Web și puteți adăuga un paragraf deasupra listei pentru a descrie ce este o listă cu, dacă vă place!

Ce zici dacă vrei o listă numerotată? Este aproape la fel, dar în loc de `<ul>`, folosiți `<ol>`. O listă numerotată este , de asemenea , numit un **comandat** listă.

- Adăugați următorul cod sub codul pe care tocmai l-ați scris - asigurați-vă că este sub **sub** eticheta `</ul>`!

```html
    <p>
        Produsele mele preferate de a mânca și bea în Irlanda sunt:
    </p>
    <ol>
        <li>Ceai</li>
        <li>Sandviciuri crud</li>
        <li>Cârnați</li>
    </ol>
```

Iată cum ar trebui să arate acum:

![Lista ordonata](images/egOrderedList.png)

\--- provocare \---

## Provocare: adăugați stil la listele tale

- Vedeți dacă puteți adăuga **reguli CSS** în foaia de stil pentru a modifica modul în care arată listele dvs.

\--- /provocare \---