## Prima pagină Web!

- În panoul din stânga-parte, **panoul de cod**, faceți clic pe tab - ul care spune `index.html`.

- Găsiți linia care spune `Bine ați venit în Irlanda!` și schimbați-l la mesajul dvs. - aveți grijă **nu** pentru a șterge etichetele`<p>` la începutul liniei și `</p>` la sfârșitul liniei. Ar trebui să vedeți actualizarea paginii dvs. web în panoul din partea dreaptă.

![Exemplul paragrafului HTML](images/egFirstHtmlCode.png)

- Acum, pe aceeași linie, schimbați `<p>` și `</p>` la `<h1>` și `</h1>`. Observi vreo schimbare a rezultatului în dreapta?

```html
  <h1>Bine ați venit în Irlanda!</h1>
```

## \--- colaps \---

## titlu: HTML și etichetele au fost explicate

**HTML** este codul care face o pagină web.

`.html` în numele fișierului spune browser - ului că fișierul este o pagină Web, astfel încât browser - ul stie sa caute **tag - uri** spunandu - i ce să se afișeze. (Un browser este programul pe care îl utilizați pentru a căuta site-uri web, de exemplu Chrome sau Firefox.)

Elementele HTML, cum ar fi `<p>` și `</p>` definesc diferite piese dintr-o pagină, de exemplu, paragrafe, titluri sau corpuri. Piesele sunt numite **elemente**. Gândiți-vă la ele ca blocuri de construcție.

### De ce am nevoie de două etichete?

Aveți nevoie de o etichetă **deschidere** și **închidere** pentru a spune browser-ului unde elementele **încep** și **termină**. Deci, pentru un paragraf, eticheta de deschidere `<p>` spune: "Aici vine un text pe care vreau să îl afișați ca paragraf". Eticheta de închidere `</p>` indică browserului unde se termină paragraful.

Totul între etichetele `<body>` și `</body>` este pagina dvs. Web.

- Observați modul în care eticheta de închidere **întotdeauna** are o bară oblică cu `/ cu`.

\--- / colaps \---

- Încercați să schimbați numerele din contul dvs. **la rubrica** tag - uri pentru a vedea diferitele dimensiuni care le va da. Aceștia pot merge de la `<h1>` până la `<h6>`. Nu uitați să modificați atât eticheta de deschidere,

- Găsiți codul pentru paragraful care spune `Site-ul meu este despre Irlanda.` și schimbați-l astfel încât să pară următoarele:

```html
  <p>
    <em>Site-ul meu</em> este de aproximativ <strong>Irlanda</strong>. 
    Va avea următoarele pagini: Atracții, Muzică, Alimentație
  </p>
```

Puteți să aflați ce fac etichetele `<em> </em>` și `<strong> </strong>`?

![Exemplu de etichete HTML](images/egFirstTags.png)

\--- provocare \---

## Provocare: adăugați mai mult text propriu

- Încercați să adăugați un nou paragraf sau o rubrică în pagina utilizând câteva dintre etichetele pe care le-ați învățat.

\--- sugestii \---

\--- sugestie \--- Când doriți să puneți text pe o pagină, trebuie să o puneți între două etichete care îi spun browserului cum să vă afișeze textul. De exemplu, etichetele `<p> </p>` informează browserul că orice este între ele este un nou paragraf de text, iar etichetele `<h1> </h1>` spun că textul între ele este o rubrică.

\--- / indiciu \---

\--- hint \---

Codul pentru paragrafe arată astfel:

```html
  <p>Acesta este un paragraf din text.</p>

  <p>Acesta este un alt paragraf.
  Totul între un set de etichete p este afișat împreună într-o singură linie lungă de pe pagina web.</p>
```

\--- / indiciu \---

\--- hint \---

Codul titlurilor arată astfel:

```html
  <h1>Aceasta este o rubrică.</h1>
```

În mod normal, rubricile vor fi afișate mai mari sau mai îndrăznețe decât paragrafele.

\--- / indiciu \---

\--- / sugestii \---

\--- /provocare \---

Felicitări, ați construit prima pagină web! Pe următoarea carte, veți afla cum să controlați cum arată.