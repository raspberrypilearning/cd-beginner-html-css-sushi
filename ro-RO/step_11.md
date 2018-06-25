## Navigarea pe site-ul dvs. web

Multe site - uri au un **de navigare** meniu pentru a ajuta vizitatorii deplasa între pagini. Acum, că aveți o mulțime de pagini, o pagină de pornire și linkuri către fiecare pagină, hai să mutăm lista de linkuri către o secțiune de navigare din partea de sus a fiecărei pagini.

![Exemplu de pagină web cu legături de navigare în partea de sus](images/egNavLinksAtTop.png)

- Găsiți codul pentru lista dvs. de linkuri pe care le-ați creat în etapa anterioară.

- Chiar înainte de eticheta de deschidere `<ul>` , apăsați **Enter** pentru a crea o linie nouă, apoi pe noua linie introduceți următoarea etichetă: `<nav>`. Trinket adaugă automat eticheta de închidere imediat după, dar o puteți șterge - nu este în locul potrivit.

- Doar **după** eticheta de închidere `</ul>` , apăsați **Introduceți** pentru a crea o linie nouă și introduceți eticheta de închidere `</nav>` acolo.

- Acum, selectați întreaga secțiune și listă `<nav>` făcând clic înainte de eticheta de deschidere `<nav>` și trăgând mouse-ul până la sfârșitul etichetei `</nav>` , astfel încât tot textul, inclusiv etichetele de deschidere și de închidere devine evidențiat. Asigurați - vă că toate **corniere** `<` și `>` la începutul și sfârșitul sunt evidențiate, de asemenea!

![Textul din stânga nu este complet selectat în timp ce textul din dreapta este](images/egSelectedYayWoops.png)

- Urmezi **tăiat** data asta în loc de copiere. Țineți apăsată tasta <kbd>Ctrl</kbd> (sau <kbd>cmd</kbd>), iar în timp ce țineți apăsată tasta <kbd>X</kbd>. Codul evidențiat va dispărea, dar nu va intra în panică!

- În partea de sus a fișierului, faceți clic în spațiul dintre etichetele `<header> </header>`. Asigurați-vă că vedeți cursorul care clipește acolo. Acum lipiți codul apăsând <kbd>Ctrl</kbd> (sau <kbd>cmd</kbd>) și <kbd>V</kbd> ca de obicei. Codul ar trebui să arate astfel:

```html
    <header>
        <nav>
            <ul>
            <li><a href="index.html">Acasă</a></li>
            <li><a href="attractions.html">Locuri de vizitat</a></li>
            <li><a href="music.html">Muzică</a></li>
            <li><a href="food.html">Lucruri de mâncare</a></li>
            </ul>
        </nav>
    </header>
```

## \--- colaps \---

## titlu: Anulează!

Dacă faceți o greșeală, puteți **anula** prin apăsarea <kbd>Ctrl</kbd> (sau <kbd>cmd</kbd>) și <kbd>Z</kbd> împreună. De obicei, puteți apăsa de câteva ori această combinație de taste pentru a anula ultimele modificări. Aceasta este o altă comandă rapidă pe care o puteți utiliza în multe programe!

\--- / colaps \---

- Încercați legăturile dvs. pentru a vă asigura că încă mai funcționează.

\--- provocare \---

## Provocare: meniuri de navigare pentru toate paginile

- Puneți această secțiune de cod în secțiunea antet a fiecărui fișier HTML pe care l-ați creat. Acest lucru va face ca meniul de navigare să apară în partea de sus a fiecărei pagini de pe site-ul dvs. Web.
    
    \--- sugestii \---
    
    \--- Sugestie \--- Selectați întreaga secțiune `<nav>` cum ați făcut înainte și apăsați pe tastele <kbd>Ctrl</kbd> (sau <kbd>cmd</kbd>) și <kbd>C</kbd> împreună pentru ao copia.

Apoi, în fiecare din fișierele dvs. `.html` , faceți clic pe secțiunea `<header> </header>` și lipiți codul exact așa cum ați făcut mai devreme. \--- / indiciu \---

\--- / sugestii \---

Acum veți putea să faceți clic pe linkuri indiferent de pagina pe care vă aflați.

\--- /provocare \---