## Een menubalk maken

Op deze kaart ziet je hoe je jouw navigatiemenu kunt transformeren in een cool uitziende menubalk, gewoon door meer CSS-regels toe te voegen aan de stylesheet.

![Example of a menu bar](images/egCoolMenuBar.png)

- Ga naar het stijlblad in de ` styles.css ` tab. Klik **onder ** een sluit accolade `} ` en druk op ** Enter ** om een ​​nieuwe lege regel te maken. Voeg de volgende CSS code in:

```css
    nav ul {
        background-color: tomato;
    }
```

Merk op hoe je twee selectors gebruikte in plaats van één? Als je alleen de ` ul ` selector zou hebben gebruikt, zou de regel van invloed zijn op alle ongeordende lijsten op je website. Adding the `nav` selector as well makes it only apply to lists that are in between `nav` tags.

![List with red background](images/egMenuBarFirstStyle.png)

Let's get rid of the bullet points. Those are the dots in front of each list item.

- Add the following to the `styles.css` file. Again, type it on a new line after a `}` so it's not inside any other block of rules.

```css
    nav ul li {
        list-style-type: none;
    }
```

Notice this set of rules has three selectors: it selects all `li` elements that are in a `ul` list which is inside a `nav` section. Phew!

![List with bullet points removed](images/egMenuBarNoBullets.png)

Now let's make the list horizontal (across) instead of vertical (down).

- Inside the new CSS rule you just created, add the following line: `display: inline;`.

![](images/egMenuBarInline.png)

- The menu items are now all squashed together, so let's also add the properties `margin-right` and `margin-left` to space them out a bit. The block of CSS code should look like this now:

```css
    nav ul li {
        list-style-type: none;
        display: inline;
        margin-right: 10px;
        margin-left: 10px;
    }
```

Remember: `10px` means ten pixels.

How about making the menu change to tell you which page you are on? This part won't be in the style sheet.

- Start with the homepage. Go to the `index.html` file. In the list of menu links, remove the link tags before and after the word `Home`, so that the list item for the homepage is just text in between `<li> </li>` tags, like this: `<li>Home</li>`.

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