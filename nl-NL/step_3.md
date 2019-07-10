## Je eerste webpagina!

- Klik in het linker deelvenster (**het codepaneel**), op het tabblad `index.html`.

- Zoek de regel met `Welkom in Ierland!` en verander het in je eigen bericht - wees voorzichtig dat je **niet** de tags `<p>` aan het begin van de regel en `</p>` aan het einde van de regel wist. Je zou de update van je webpagina in het rechter paneel moeten zien.

![HTML paragraph example](images/egFirstHtmlCode.png)

- Verander nu op dezelfde regel de `<p>` en ` </p>` door `<h1>` en ` </h1>`. Zie je de verandering aan de rechterkant?

```html
  <h1> Welkom in Ierland! </h1>
```

## \--- collapse \---

## title: HTML en tags uitgelegd

**HTML** is de code die een webpagina maakt.

De `.html ` in de bestandsnaam vertelt de browser dat het bestand een webpagina is, waarna de browser naar ** tags ** (label) zoekt welke hem vertellen wat hij moet weergeven. (Een browser is het programma dat je gebruikt om naar websites te kijken, bijvoorbeeld Chrome of Firefox.)

HTML-tags zoals `<p>` en ` </p>` definiëren verschillende delen van een pagina, bijvoorbeeld alinea's, koppen of de inhoud. Deze delen worden **elements ** (elementen) genoemd. Zie ze als bouwstenen.

### Waarom heb ik twee tags nodig?

Je hebt een **open** en een **closing ** (sluit) tag nodig om de browser te vertellen waar de elementen **starten** en **eindigen**. Dus voor een alinea, de opening tag `<p>` zegt "Hier komt wat tekst die ik wil weergeven als een alinea." De afsluitende tag `</p>` vertelt de browser waar de alinea eindigt.

Alles tussen de `<body>` en ` </body>` tags is je webpagina.

- Let er op dat de afsluitende tag **altijd** een schuine streep ` / ` naar voren heeft.

\--- /collapse \---

- Probeer de cijfers in je **heading** tags te wijzigen om de verschillende mogelijkheden te zien. Ze kunnen gaan van `<h1>` helemaal tot aan de `<h6>`. Vergeet niet om zowel de open tag als de sluit tag te wijzigen, zodat ze overeenkomen.

- Zoek de code voor de alinea met de tekst `Mijn website gaat over Ierland` en verander het zodat het er zo uitziet:

```html
  <p> <em>Mijn website</em> gaat over <strong>Ierland</strong>. 
    Het gaat de pagina's: Attracties, Muziek en Eten bevatten
  </p>
```

Weet jij wat de `<em> </em>` en `<strong> </strong>` tags doen?

![Example of HTML tags](images/egFirstTags.png)

\--- challenge \---

## Uitdaging: voeg nog wat meer eigen tekst toe

- Probeer een nieuwe alinea of ​​kop aan je pagina toe te voegen met behulp van enkele van de tags die je hebt geleerd.

\--- hints \---

\--- hint \--- Als je tekst op een pagina wilt plaatsen, moet je deze tussen twee tags plaatsen die je browser vertellen hoe jouw tekst moet worden weergegeven. Bijvoorbeeld de `<p> </p>` tags vertellen de browser dat alles wat er tussenin zit een nieuwe alinea is en de `<h1> </h1>` tags vertellen dat de tekst ertussen een heading (kop) is.

\--- /hint \---

\--- hint \---

De code voor alinea's (paragraphs) ziet er als volgt uit:

```html
  <p>Dit is een alinea tekst.</p> 

   <p>Dit is een andere alinea.
  Alles tussen de twee p-tags wordt samen weergegeven in één lange regel op de webpagina. </p>
```

\--- /hint \---

\--- hint \---

De code voor kopteksten (headings) ziet er als volgt uit:

```html
  <h1>Dit is een kop.</h1>
```

Koppen worden normaal gesproken groter of dikker weergegeven dan de alinea's.

\--- /hint \---

\--- /hints \---

\--- /challenge \---

Gefeliciteerd, je hebt je eerste webpagina gebouwd! Op de volgende kaart kom je erachter hoe je kunt bepalen hoe alles eruit ziet.