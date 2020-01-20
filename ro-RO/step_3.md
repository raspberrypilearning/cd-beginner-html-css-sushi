## Prima ta pagină web!

- În partea stângă a panoului, **panoul pentru cod**, dă click pe tab-ul pe care scrie `index.html`.

- Găsește linia care spune `Bun venit în Irlanda!` și schimb-o pentru a folosi propriul tău mesaj — ai grijă să **nu** șterge etichetele `<p>` de la începutul liniei și `</p>` de la sfârșitul liniei. Ar trebui să vezi cum pagina ta web se actualizează în partea dreaptă a panoului.

![HTML paragraph example](images/egFirstHtmlCode.png)

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

Everything in between the `<body>` and `</body>` tags is your webpage.

- Notice how the closing tag **always** has a forward slash `/`.

\--- / colaps \---

- Try changing the numbers in your **heading** tags to see the different sizes they give you. They can go from `<h1>` all the way up to `<h6>`. Remember to change both the opening and closing tag so that they match.

- Find the code for the paragraph that says `My website is about Ireland.` and change it so that it looks like this:

```html
  <p>
    <em>My website</em> is about <strong>Ireland</strong>. 
    It is going to have the following pages: Attractions, Music, Food
  </p>
```

Can you work out what the `<em> </em>` and `<strong> </strong>` tags do?

![Example of HTML tags](images/egFirstTags.png)

\--- challenge \---

## Challenge: add some more text of your own

- Try adding a new paragraph or heading to your page using some of the tags you've learned about.

\--- hints \---

\--- hint \--- When you want to put text on a page, you need to put it in between two tags that tell your browser how to display your text. For example, the `<p> </p>` tags tell the browser that whatever is in between them is a new paragraph of text, and the `<h1> </h1>` tags tell it that the text in between is a heading.

\--- /hint \---

\--- hint \---

The code for paragraphs looks like this:

```html
  <p>This is one paragraph of text.</p>

  <p>This is another paragraph.
  Everything in between one set of p tags is 
  displayed together in one long line on the webpage.</p>
```

\--- /hint \---

\--- hint \---

The code for headings looks like this:

```html
  <h1>This is a heading.</h1>
```

Headings will normally be displayed bigger or bolder than the paragraphs.

\--- /hint \---

\--- /hints \---

\--- /challenge \---

Congratulations, you've built your first webpage! On the next card, you'll find out how to control how it looks.