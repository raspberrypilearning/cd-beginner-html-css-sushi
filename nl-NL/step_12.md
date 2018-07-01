## Een menubalk maken

Op deze kaart ziet je hoe je jouw navigatiemenu kunt transformeren in een cool uitziende menubalk, gewoon door meer CSS-regels toe te voegen aan de stylesheet.

![Example of a menu bar](images/egCoolMenuBar.png)

- Ga naar het stijlblad in de ` styles.css ` tab. Klik **onder ** een sluit accolade `} ` en druk op ** Enter ** om een ​​nieuwe lege regel te maken. Voeg de volgende CSS code in:

```css
    nav ul {
        background-color: tomato;
    }
```

Merk op hoe je twee selectors gebruikte in plaats van één? Als je alleen de ` ul ` selector zou hebben gebruikt, zou de regel van invloed zijn op alle ongeordende lijsten op je website. Het toeveogen van de `nav ` selector maakt het alleen van toepassing op lijsten die tussen ` nav` tags staan.

![List with red background](images/egMenuBarFirstStyle.png)

Laten we de opsommingstekens verwijderen. Dat zijn de stippen voor elk lijst item.

- Voeg de volgende code toe aan het `style.css` bestand. Typ na een `} ` opnieuw een nieuwe regel zodat het niet in een ander regelsysteem zit.

```css
    nav ul li {
        list-style-type: none;
    }
```

Merk op dat deze set regels drie selectors heeft: het selecteert alle ` li ` elementen die zich in een ` ul ` lijst bevinden, die zich binnen een ` nav ` sectie bevinden. Oef!

![List with bullet points removed](images/egMenuBarNoBullets.png)

Laten we nu de lijst in plaats van verticaal (naar beneden) horizontaal (over de breedte) maken.

- Binnen de nieuwe CSS-regel die je zojuist hebt gemaakt, voeg je de volgende regel toe: `display: inline;`.

![](images/egMenuBarInline.png)

- De menu-items zijn nu allemaal samen geplet, dus laten we ook de eigenschappen `margin-right` (ruimte rechts) en `margin-left ` (ruimte links) toevoegen om ze een beetje te spreiden. Het blok CSS-code zou er nu als volgt uit moeten zien:

```css
    nav ul li {
        list-style-type: none;
        display: inline;
        margin-right: 10px;
        margin-left: 10px;
    }
```

Onthoud: ` 10px ` betekent tien pixels.

Hoe zou het zijn om het menu te veranderen zodat het vertelt op welke pagina je je bevindt? Dit onderdeel staat niet in de stylesheet.

- Begin met de startpagina. Ga naar de ` index.html `. In the list of menu links, remove the link tags before and after the word `Home`, so that the list item for the homepage is just text in between `<li> </li>` tags, like this: `<li>Home</li>`.

- Now go to each of your other files, and do the same thing, each time removing the link tags for the page you are editing. So, for example, on the `music.html` file, I've removed the link tags in the `Music` list item:

```html
    <header>
        <nav>
            <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="attractions.html">Places to visit</a></li>
            <li>Music</li>
            <li><a href="food.html">Things to eat</a></li>
            </ul>
        </nav>
    </header>
```

- Explore your pages by clicking the links. See how the menu bar shows the page you're on as plain text instead of a link? 

![Example of menu bar highlighting current page](images/egMenuBarOnPage.png)

On the next card you'll learn even more CSS tricks to make the menu bar look awesome.