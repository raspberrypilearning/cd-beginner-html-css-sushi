## Een lijst maken

Nu leer je hoe je een lijst met items, zoals "eenhoorns, robots, katten", in een mooier uitziende lijst kunt veranderen zodat je er later heel leuke dingen mee kan doen.

- Voeg in het ` index.html ` bestand, net boven de regel met ` </main>` de volgende code toe:

```html
    <ul>
        <li>Koeien</li>
        <li>Schapen</li>
        <li>Vossen</li>
        <li>Vleermuizen</li>
    </ul>
```

Het resultaat zou een mooie lijst als deze moeten zijn:

![Unordered list](images/egUnorderedList.png)

Merk steeds een aparte paar `<li></li>` tags rond elk item in de lijst op.

Dit is een lijst van enkele dieren je in Nederland kunt zien. Je kunt de items in de lijst wijzigen in dingen die logisch zijn voor jouw website, en een alinea boven de lijst toevoegen om te beschrijven wat de lijst bevat, als je dat wilt!

Wat dacht je ervan een genummerde lijst te maken? Het is bijna hetzelfde, maar in plaats van `<ul>` gebruikt je `<ol>`. A numbered list is also called an **ordered** list.

- Add the following code below the code you just wrote — make sure it's **below** the `</ul>` tag!

```html
    <p>
        My favourite things to eat and drink in Ireland are:
    </p>
    <ol>
        <li>Tea</li>
        <li>Crisp sandwiches</li>
        <li>Sausages</li>
    </ol>
```

Here's what it should look like now:

![Ordered list](images/egOrderedList.png)

\--- challenge \---

## Challenge: add style to your lists

- See if you can add **CSS rules** to your stylesheet to change how your lists look.

\--- /challenge \---