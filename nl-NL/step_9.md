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

- Klik in je trinket tussen de aanhalingstekens na ` href = ` en druk tegelijkertijd op de <kdb>Ctrl</kdb> (of <kdb>cmd</kdb>) en <kdb>V</kdb> toetsen om de URL die je zojuist gekopieerd hebt te plakken. Je code zou er ongeveer als volgt uit moeten zien:

```html
  <a href="https://nl. wikipedia. org/wiki/Nederland"> Klik hier </a>
```

Je hebt zojuist je eerste link gemaakt! Klik erop om te zien of het nu werkt.

![Link tag](images/egLinkTagWithURL.png)

## \--- collapse \---

## titel: links naar andere websites

Trinket heeft met sommige webadressen problemen. Je kunt desgewenst URL's van andere websites dan Wikipedia proberen, maar deze werken mogelijk niet in jouw trinket. Als je echter je project zou downloaden en de bestanden in een webbrowser zou zien, zouden de koppelingen moeten werken.

\--- /collapse \---

- Probeer in plaats van de woorden ` Klik hier `, een foto tussen de `<a> </a>` tags te plaatsen, zoals hier:

```html
  <a href="https://nl. wikipedia. org/wiki/Nederland">
      <img src="tito. png" alt="Tito the dog" width="100px" />
  </a>
```

- Klik op de afbeelding. Zie je dat het een link is geworden?

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