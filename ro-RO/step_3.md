## Prima ta pagină web!

- În partea stângă a panoului, **panoul pentru cod**, dă click pe tab-ul pe care scrie `index.html`.

- Găsește linia care spune `Bun venit în Irlanda!` și schimb-o pentru a folosi propriul tău mesaj — ai grijă să **nu** șterge etichetele `<p>` de la începutul liniei și `</p>` de la sfârșitul liniei. Ar trebui să vezi cum pagina ta web se actualizează în partea dreaptă a panoului.

![Exemplu de paragaf HTML](images/egFirstHtmlCode.png)

- Acum, pe acceași linie, schimbă `<p>` și `</p>` în `<h1>` și `</h1>`. Observi vreo schimbare a rezultatului în dreapta?

```html
  <h1>Bun venit în Irlanda!</h1>
```

## \--- collapse \---

## title: Explicația etichetelor și a HTML

**HTML** este codul care creează o pagină web.

Partea `.html` dintr-un nume de fișier îi spune browser-ului faptul că fișierul este o pagină web, astfel că browser-ul caută **etichete** pentru a decide ce să afișeze. (Un browser este programul pe care îl folosești pentru a naviga pe website-uri, de exemplu Chrome sau Firefox.)

Etichetele HTML precum `<p>` și `</p>` definesc diferite porțiuni dintr-o pagină, cum ar fi paragrafele, titlurile sau conținutul. Porțiunile respective sunt numite **elemente**. Gândește-te la ele ca blocuri de construcții.

### De ce am nevoie de două etichete?

Aveți nevoie de o etichetă de **deschidere** și una de **închidere** pentru a spune browser-ului unde **încep** și unde se **termină** elementele. Deci, pentru un paragraf, eticheta de deschidere `<p>` spune: „Aici vine un text pe care vreau să îl afișezi ca paragraf”. Eticheta de închidere `</p>` indică browserului unde se termină paragraful.

Totul între etichetele `<body>` și `</body>` constituie conținutul paginii tale web.

- Observă faptul că etichetele pentru închidere au **întotdeauna** un slash `/`.

\--- /collapse \---

- Încearcă să schimbi numerele din etichetele pentru **titluri** pentru a vedea diferitele mărimi pe care acestea le oferă. Ele merg de la `<h1>` până la `<h6>`. Nu uitați să modifici atât eticheta de deschidere, cât și cea de închidere.

- Găsește codul din paragraf care spune `Website-ul meu este despre Irlanda.` și schimbă-l pentru ca acesta să arate astfel:

```html
  <p>
    <em>Website-ul meu</em> este despre <strong>Irlanda</strong>. 
    Va avea următoarele pagini: atracții, muzică, mâncare
  </p>
```

Poți să îți dai seama ce fac etichetele `<em> </em>` și `<strong> </strong>`?

![Exemplu de etichete HTML](images/egFirstTags.png)

\--- challenge \---

## Provocare: adaugă mai mult text personalizat

- Încearcă să adaugi un nou paragraf sau titlu la pagina ta folosind câteva dintre etichetele despre care ai aflat.

\--- hints \---

\--- hint \---

When you want to put text on a page, you need to put it in between two tags that tell your browser how to display your text. For example, the `<p> </p>` tags tell the browser that whatever is in between them is a new paragraph of text, and the `<h1> </h1>` tags tell it that the text in between is a heading.

\--- /hint \---

\--- hint \---

The code for paragraphs looks like this:

```html
  <p>Acesta este un paragraf de text.</p>

  <p>Acesta este un alt paragraf.
  Conținutul dintre o pereche de etichete p este  
  afișat împreună într-o linie lungă pe pagina web.</p>
```

\--- /hint \---

\--- hint \---

The code for headings looks like this:

```html
  <h1>Acesta este un titlu.</h1>
```

Headings will normally be displayed bigger or bolder than the paragraphs.

\--- /hint \---

\--- /hints \---

\--- /challenge \---

Congratulations, you've built your first webpage! On the next card, you'll find out how to control how it looks.