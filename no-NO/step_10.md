## Navigating your website

Many websites have a **navigation** menu to help visitors move between pages. Now that you've got a bunch of pages, a homepage, and links to each page, let's move the list of links to a navigation section at the top of every page.

![Example of a web page with navigation links at the top](images/egNavLinksAtTop.png)

- Find the code for your list of links that you created in the previous step.

- Just before the opening `<ul>` tag, press **Enter** to create a new blank line, then on the new line type the following tag: `<nav>`. Trinket automatically adds the closing tag right after, but you can delete that — it's not in the right place.

- Just **after** the closing `</ul>` tag, press **Enter** to create a new blank line, and type in the closing tag `</nav>` there.

- Now select your entire `<nav>` section and list by clicking just before the opening `<nav>` tag and dragging the mouse all the way down to just after the closing `</nav>` tag, so that all of the text including the opening and closing tags becomes highlighted. Make sure all of the **angle brackets** `<` and `>` at the start and end are highlighted as well!

![Text on the left is not fully selected while the text on the right is](images/egSelectedYayWoops.png)

- You are going to **cut** this time instead of copying. Hold down the <kbd>Ctrl</kbd> (or <kbd>cmd</kbd>) key, and while holding it, press the <kbd>X</kbd> key. The highlighted code will disappear, but don't panic!

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
    
    \--- hint \---

Select the entire `<nav>` section like you did before, and press the <kbd>Ctrl</kbd> (or <kbd>cmd</kbd>) and <kbd>C</kbd> keys together to copy it.

Then, in each of your `.html` files, click inside the `<header> </header>` section and paste the code exactly like you did earlier.

\--- /hint \---

\--- /hints \---

Now you will be able to click the links no matter which page you are on.

\--- /challenge \---