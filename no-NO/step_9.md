## Adding more pages

This card will show you how to add more pages to your website.

- At the top of the code panel, click on the **+** symbol next to the tabs, and type in a name for your new file. It must end in `.html` (including the dot!) so that the browser knows it's a webpage.

![Adding a new file in Trinket](images/tktNewFileArrows.png)

## \--- kollaps \---

## title: Renaming or deleting a file

If you want to change the name of a file, click on the **cog** icon to the right of the file name, and then click the **pencil** icon. Type in the new name and press **Enter**. You can also delete a file by clicking the **bin** icon instead of the **pencil** icon. ![](images/EditFilename.png)

You might be wondering why you can't change the name of the `index.html` file. `index.html` is a special name used for the **homepage** of a website. That's the first page you land on when you visit a website. Whenever you go to a website's homepage, the browser looks for the file called `index.html` and displays it on your screen.

\--- /collapse \---

- Find the file `blank_page.html` and copy and paste all of the code from it into your new file. Since you want to copy the whole thing, you can click anywhere on the code and use the keyboard shortcut <kbd>Ctrl</kbd> (or <kbd>cmd</kbd>) and <kbd>A</kbd> to select all of it at once.

- Change the text in between the `<title> </title>` tags so your new page has a suitable title. Trinket won't display the title, but you can see it at the top of your browser window if you download your project.

![The page title showing in the browser tab](images/egLocalFileWindowTitle.png)

- In between the `<main> </main>` tags in the new file, use the tags you have learned about to add stuff to the page, such as paragraphs, headings, images, and lists!

- Repeat the steps above for each new page that you want to add.

When there are too many tabs for Trinket to show at once, you can use the **<** and **>** icons in the top left-hand corner of the tabs to scroll between them.

![The buttons for scrolling the tabs](images/tktScrollTabIcons.png)

Now you need to make links so that you can get to each of your new pages! Let's put all the links in a list.

- In the `index.html` file, add the following code to the body of your webpage:

```html
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="attractions.html">Places to visit</a></li>
        <li><a href="music.html">Music</a></li>
        <li><a href="food.html">Things to eat</a></li>
    </ul>
```

- Change the value of the `href` attribute for each link (remember, that's the text inside the quotation marks) so that it exactly matches the name of each HTML file that you have created.

- Change the text in between the `<a> </a>` tags to suitable descriptions of your pages.

Now you can navigate to your new pages!

![Example list of links on a web page](images/egListOfPageLinks.png)