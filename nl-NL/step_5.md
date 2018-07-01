## Bepalen hoe het eruit ziet

De code die beschrijft hoe een website eruit ziet, wordt ** CSS** genoemd.

- Kijk naar de tabbladen bovenaan het codepaneel en ga naar het bestand ` styles.css ` door op het tabblad met die naam te klikken. Het bestand bevat de volgende tekst:

```css
  body {
      background-color: white;
  }
```

- Verander de kleur `white` (wit) naar ` LightSkyBlue `(lichtblauw) en kijk wat er gebeurt. Je website zou nu een blauwe achtergrond moeten hebben! 

![Example with blue background](images/egFirstCSSbluebg.png)

## \--- collapse \---

## titel: Hoe werkt het?

Als je naar de bovenkant van het `index.html` bestand kijkt, zie je de volgende regel:

```html
  <link type="text/css" rel="stylesheet" href="styles.css"/>
```

De bovenstaande regel vertelt de browser om te zoeken naar een speciaal bestand met de naam ` styles.css `. Dit speciale bestand wordt een ** stylesheet ** genoemd. Je kunt een style sheet (opmaakbestand) herkennen door de `.css` in de naam.

Een style sheet bevat ** -regels ** voor hoe elk element op je webpagina eruit zou moeten zien.

De accolades `{ }` en de code ertussen is een set van ** CSS-regels ** . Het woord ` body` betekent dat de regels voor alle `< body>` elementen op je website gelden. We noemen het woord voor de accolades een **selector **. Dus in dit geval is het de selector voor de body elementen.

Elke regel binnen de accolades bestaat uit:

- A **property** on the left, followed by a colon symbol `:`
- A **value** for the property on the right-hand side after the colon
- A semi-colon symbol `;` at the end

\--- /collapse \---

- Lets add rules to change how the text looks. Add two new lines inside the curly braces:

```css
  body {
    background-color: LightSkyBlue;
    font-family: "Helvetica", sans-serif;
    color: purple;
  }
```

Look at how this has changed the webpage.

The `color` property is always for text. Here, you are setting the colour of all text in the `body` of your webpage.

- You can also write separate rules for the headings and the paragraphs. For `<h1>` headings, you use the `h1` selector. Below the closing curly brace containing the CSS rule for the body, add the following code.

```css
  h1 {
    color: orange;
    font-family: "Times New Roman", serif;
  }
```

Your heading text should be orange now, with the paragraph in purple as before.

![Result of new CSS code](images/egCssColorsFonts.png)

Notice how the letters also look different as well as being a different colour? This is because you changed their **font family**. You can find some more fonts [here](http://dojo.soy/web-font-families).

- Try adding a set of rules for the `<h2>` headings, using the `h2` selector.

- Why not experiment with different colour combinations for the text and background? There are lots of colours available to use. Find a full list of them [here](http://dojo.soy/web-color-names).