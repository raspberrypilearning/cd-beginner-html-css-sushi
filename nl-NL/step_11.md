## Navigeren door je website

Veel websites hebben een ** navigatie ** menu om bezoekers tussen pagina's te laten navigeren. Nu je meerdere pagina's, een startpagina en koppelingen naar elke pagina hebt, kunt je de lijst met koppelingen verplaatsen naar een navigatie gedeelte boven aan elke pagina.

![Example of a web page with navigation links at the top](images/egNavLinksAtTop.png)

- Zoek de code voor je lijst met links die je in de vorige stap hebt gemaakt.

- Druk vlak voor de opening `<ul>` -tag op ** Enter ** om een ​​nieuwe lege regel te maken, typ dan op de nieuwe regel de volgende tag: `<nav>`. Trinket voegt de sluit tag automatisch direct hierna toe, maar je kunt die verwijderen - hij staat niet op de juiste plaats.

- Druk vlak **na** de sluit `</ul>` -tag op ** Enter ** om een ​​nieuwe lege regel te maken, typ dan op de nieuwe regel de volgende tag: `</nav>`.

- Selecteer nu je gehele `<nav>` gedeelte en lijst door net vóór de `<nav>` -tag te klikken en de muis helemaal naar beneden te slepen tot net na de ` </nav>` tag, zodat alle tekst inclusief de open en sluit tags worden gemarkeerd. Zorg ervoor dat alle ** punthaken ** `<` en `>` aan het begin en einde ook zijn gemarkeerd!

![Text on the left is not fully selected while the text on the right is](images/egSelectedYayWoops.png)

- Je gaat deze keer ** knippen ** in plaats van kopiëren. Hold down the <kbd>Ctrl</kbd> (or <kbd>cmd</kbd>) key, and while holding it, press the <kbd>X</kbd> key. The highlighted code will disappear, but don't panic!

- At the top of the file, click in the space between the `<header> </header>` tags. Make sure you see the cursor flashing there. Now paste in the code by pressing <kbd>Ctrl</kbd> (or <kbd>cmd</kbd>) and <kbd>V</kbd> as usual. The code should look something like this:

```html
    <header>
        <nav>
            <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="attractions.html">Places to visit</a></li>
            <li><a href="music.html">Music</a></li>
            <li><a href="food.html">Things to eat</a></li>
            </ul>
        </nav>
    </header>
```

## \--- collapse \---

## title: Undo!

If you make a mistake, you can **undo** it by pressing <kbd>Ctrl</kbd> (or <kbd>cmd</kbd>) and <kbd>Z</kbd> together. You can usually press this key combination a few times to undo the last few changes. This is another handy keyboard shortcut that you can use in many programs!

\--- /collapse \---

- Try out your links to make sure they are still working.

\--- challenge \---

## Challenge: navigation menus for all pages

- Put this code section into the header section of each HTML file that you've created. This will make the navigation menu appear at the top of every page on your website.
    
    \--- hints \---
    
    \--- hint \--- Select the entire `<nav>` section like you did before, and press the <kbd>Ctrl</kbd> (or <kbd>cmd</kbd>) and <kbd>C</kbd> keys together to copy it.

Then, in each of your `.html` files, click inside the `<header> </header>` section and paste the code exactly like you did earlier. \--- /hint \---

\--- /hints \---

Now you will be able to click the links no matter which page you are on.

\--- /challenge \---