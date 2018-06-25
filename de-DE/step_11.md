## Navigieren auf Ihrer Website

Viele Websites verfügen über ein Menü **Navigation** , um Besuchern den Wechsel zwischen den Seiten zu erleichtern. Nun, da Sie eine Reihe von Seiten, eine Startseite und Links zu jeder Seite haben, verschieben Sie die Liste der Links zu einem Navigationsbereich oben auf jeder Seite.

![Beispiel für eine Webseite mit Navigationslinks oben](images/egNavLinksAtTop.png)

- Suchen Sie den Code für Ihre Liste der Links, die Sie im vorherigen Schritt erstellt haben.

- Kurz vor dem öffnenden Tag `<ul>` drücken Sie **Geben Sie** , um eine neue leere Zeile zu erstellen, und geben Sie in der neuen Zeile das folgende Tag ein: `<nav>`. Trinket fügt automatisch das schließende Tag direkt danach hinzu, aber Sie können das löschen - es ist nicht an der richtigen Stelle.

- Nur **nach** der schließenden `</ul>` Tag, drücken Sie **Geben Sie** , um eine neue leere Zeile zu erstellen, und geben Sie dort das schließende Tag `</nav>` ein.

- Wählen Sie nun Ihren gesamten `<nav>` Abschnitt und die Liste aus, indem Sie kurz vor dem öffnenden `<nav>` -Tag klicken und die Maus ganz nach unten bis kurz nach dem schließenden `</nav>` -Tag ziehen, so dass der gesamte Text einschließlich der öffnenden und schließenden Tags angezeigt wird wird hervorgehoben. Stellen Sie sicher, dass alle **Winkel** `<` und `>` am Anfang und Ende markiert sind!

![Der Text auf der linken Seite ist nicht vollständig ausgewählt, während der Text auf der rechten Seite ist](images/egSelectedYayWoops.png)

- Sie werden auf **Schnitt** diesmal anstelle des Kopierens. Halten Sie die Taste <kbd>Ctrl</kbd> (oder <kbd>cmd</kbd>) gedrückt, und halten Sie sie gedrückt, und drücken Sie die Taste <kbd>X</kbd>. Der hervorgehobene Code wird verschwinden, aber keine Panik!

- Klicken Sie oben in der Datei in den Bereich zwischen den `<header> </header>` -Tags. Stellen Sie sicher, dass der Cursor dort blinkt. Fügen Sie nun den Code ein, indem Sie wie üblich <kbd>Ctrl</kbd> (oder <kbd>cmd</kbd>) und <kbd>V</kbd> drücken. Der Code sollte etwa so aussehen:

```html
    <header>
        <nav>
            <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="attractions.html">Orte zu besuchen</a></li>
            <li><a href="music.html">Musik</a></li>
            <li><a href="food.html">Dinge zu essen</a></li>
            </ul>
        </nav>
    </header>
```

## \--- Einsturz \---

## Titel: Rückgängig machen!

Wenn Sie einen Fehler machen, können Sie **zurücksetzen** durch Drücken <kbd>Ctrl</kbd> (oder <kbd>cmd</kbd>) und <kbd>Z</kbd> zusammen. Sie können diese Tastenkombination normalerweise einige Male drücken, um die letzten Änderungen rückgängig zu machen. Dies ist eine weitere praktische Tastenkombination, die Sie in vielen Programmen verwenden können!

\--- / einklappen \---

- Probieren Sie Ihre Links aus, um sicherzustellen, dass sie noch funktionieren.

\--- Herausforderung \---

## Herausforderung: Navigationsmenüs für alle Seiten

- Fügen Sie diesen Codeabschnitt in den Headerabschnitt jeder HTML-Datei ein, die Sie erstellt haben. Dadurch wird das Navigationsmenü oben auf jeder Seite Ihrer Website angezeigt.
    
    \--- Hinweise \---
    
    \--- Hinweis \--- Wählen Sie den gesamten Abschnitt `<nav>` wie zuvor und drücken Sie die Tasten <kbd>Ctrl</kbd> (oder <kbd>cmd</kbd>) und <kbd>C</kbd> , um sie zu kopieren.

Klicken Sie dann in jeder Ihrer `.html` Dateien in den Abschnitt `<header> </header>` und fügen Sie den Code genau wie zuvor ein. \--- /Hinweis \---

\--- / Hinweise \---

Jetzt können Sie auf die Links klicken, egal auf welcher Seite Sie sich gerade befinden.

\--- /Herausforderung \---