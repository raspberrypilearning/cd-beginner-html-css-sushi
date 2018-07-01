## Links maken

Op deze kaart leer je hoe je een link kunt maken die, wanneer er op wordt geklikt, je naar een andere pagina brengt.

- Voeg de volgende code toe aan de hoofdgedeelte van ` index.html `:

```html
  <a href=""> Klik hier </a>
```

De `<a> </a>` tags veranderen alles wat er tussenin zit in een link.

- Klik op uw link om te zien wat er gebeurt. Het doet niets, toch?

Dat komt omdat het ` href ` attribuut momenteel leeg is. Het moet de ** URL ** (webadres) bevatten van de pagina waarnaar je een koppeling wilt maken.

- Ga naar Wikipedia en vind een pagina over iets op jouw website. Ik ga de pagina over Nederland gebruiken.

- Klik in de adresbalk en selecteer alle tekst in adresbalk. Dat is de volledige URL van de pagina waarop je je bevindt. Druk tegelijkertijd op de <kdb>Ctrl</kdb> (of <kdb>cmd</kdb>) en <kdb>C</kdb> toetsen om het te kopiëren.
    
    ![URL in address bar](images/AddressBarURL.png)

- Klik in je trinket tussen de aanhalingstekens na ` href = ` en druk tegelijkertijd op de <kdb>Ctrl</kdb> (of <kdb>cmd</kdb>) en <kdb>V</kdb> keys at the same time to paste in the URL you just copied. Your code should look something like this now:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">Click here</a>
```

You just created your first link! Click on it to see if it works now.

![Link tag](images/egLinkTagWithURL.png)

## \--- collapse \---

## title: Links to other websites

Trinket has trouble with some web addresses. You can try URLs of websites other than Wikipedia if you like, but they may not work in your trinket. However, if you were to download your project and view the files in a web browser, you would see the links working.

\--- /collapse \---

- Try putting a picture in between the `<a> </a>` tags instead of the words `Click here`, like this:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">
      <img src="tito.png" alt="Tito the dog" width="100px" />
  </a>
```

- Click on your picture. Do you see that it was turned into a link?

You can put a link into other elements of your webpage too, such as in a paragraph or even in a list. Here is an example of a sentence with a link in it:

```html
  <p>
    <a href="https://en.wikipedia.org/wiki/Ireland">Click here</a> to read the Wikipedia page!
  </p>
```

\--- challenge \---

## Challenge: put a link into a list

- See if you can make a list that contains a link inside one of the list items.

\--- /challenge \---