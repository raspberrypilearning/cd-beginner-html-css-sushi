## Weitere Seiten hinzufügen

Diese Karte zeigt dir, wie du weitere Seiten zu deiner Website hinzufügen kannst.

- Klicke oben im Codebereich auf das **+** Symbol neben den Tabs und gib einen Namen für deine neue Datei ein. Er muss mit `.html` enden (einschließlich des Punkts!), damit der Browser weiß, dass es sich um eine Webseite handelt.

![Hinzufügen einer neuen Datei in Trinket](images/tktNewFileArrows.png)

## \--- collapse \---

## title: Eine Datei umbenennen oder löschen

Wenn du den Namen einer Datei ändern möchtest, klicke auf das Symbol **Zahnrad**-Symbol rechts neben dem Dateinamen und anschließend auf das **Bleistift**-Symbol. Gib den neuen Namen ein und drücke **Enter**. Du kannst eine Datei auch löschen, indem du auf das**Papierkorb** Symbol anstelle des **Bleistift** Symbols klickst.

![](images/EditFilename.png)

You might be wondering why you can't change the name of the `index.html` file. `index.html` is a special name used for the **homepage** of a website. That's the first page you land on when you visit a website. Whenever you go to a website's homepage, the browser looks for the file called `index.html` and displays it on your screen.

\--- /collapse \---

- Finde die Datei `blank_page.html`, kopiere den gesamten Code darin und füge ihn in deine neue Datei ein. Da Du das Ganze kopieren möchtest, kannst Du irgendwo auf den Code klicken und die Tastenkombination <kbd>Strg</kbd> (oder <kbd>cmd</kbd>) und <kbd>A</kbd> drücken, um alles gleichzeitig auszuwählen.

- Ändere den Text zwischen den `<title> </title>` -Tags, damit Deine neue Seite einen passenden Titel hat. Trinket zeigt den Titel nicht an, aber Du kannst ihn oben im Browserfenster sehen, wenn Du Dein Projekt herunterlädst.

![The page title showing in the browser tab](images/egLocalFileWindowTitle.png)

- Zwischen den `<main> </main>` -Tags in der neuen Datei verwende die Tags, die Du gelernt hast, um Dinge wie Seiten, Überschriften, Bilder und Listen zur Seite hinzuzufügen!

- Wiederhole die obigen Schritte für jede neue Seite, die Du hinzufügen möchtest.

When there are too many tabs for Trinket to show at once, you can use the **<** and **>** icons in the top left-hand corner of the tabs to scroll between them.

![The buttons for scrolling the tabs](images/tktScrollTabIcons.png)

Now you need to make links so that you can get to each of your new pages! Let's put all the links in a list.

- Füge in der Datei `index.html` dem Textkörper (body) Deiner Webseite den folgenden Code hinzu:

```html
    <ul>
   <li><a href="index.html">Start</a></li>
   <li><a href="attractions.html">Attraktionen</a></li>
   <li><a href="music.html">Musik</a></li>
   <li><a href="food.html">Essen</a></li>
 </ul>
```

- Ändere den Wert des Attributs `href` für jeden Link (denke daran, das ist der Text in den Anführungszeichen), damit er genau mit dem Namen der einzelnen HTML-Dateien übereinstimmt, die Du erstellt hast.

- Ändere den Text zwischen den `<a> </a>` -Tags in passende Beschreibungen Deiner Seiten.

Now you can navigate to your new pages!

![Example list of links on a web page](images/egListOfPageLinks.png)