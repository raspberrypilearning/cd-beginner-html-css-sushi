## Erstellen einer Menüleiste

Auf dieser Karte sehen Sie, wie Sie Ihr Navigationsmenü in eine coole Menüleiste verwandeln können, indem Sie einfach weitere CSS-Regeln in das Stylesheet einfügen.

![Beispiel für eine Menüleiste](images/egCoolMenuBar.png)

- Wechseln Sie zur Stylesheet-Datei auf der Registerkarte `styles.css`. Klicken Sie auf **unter** eine schließende geschweifte Klammer `}`und drücken **Geben Sie** eine neue leere Zeile zu erstellen. Fügen Sie die folgende CSS-Regel hinzu:

```css
    nav ul {Hintergrundfarbe: Tomate; }
```

Beachten Sie, wie Sie zwei Selektoren statt einer verwendet haben? Wenn Sie den Selektor `ul` wirkt sich die Regel auf alle ungeordneten Listen auf Ihrer Website aus. Das Hinzufügen des `nav` Selektors trifft auch nur auf Listen zu, die zwischen `nav` -Tags liegen.

![Liste mit rotem Hintergrund](images/egMenuBarFirstStyle.png)

Lassen Sie uns die Aufzählungspunkte loswerden. Das sind die Punkte vor jedem Listenelement.

- Fügen Sie Folgendes zur Datei `styles.css`. Geben Sie es erneut in eine neue Zeile nach einer `}` damit es sich nicht in einem anderen Block von Regeln befindet.

```css
    nav ul li {Liste-Stil-Typ: keine; }
```

Beachten Sie, dass dieser Regelsatz über drei Selektoren verfügt: Er wählt alle `li` -Elemente aus, die sich in einer `ul` Liste befinden, die sich in einem `nav` Abschnitt befindet. Puh!

![Liste mit entfernten Aufzählungspunkten](images/egMenuBarNoBullets.png)

Lassen Sie uns nun die Liste horizontal (across) anstatt vertikal (down) machen.

- Fügen Sie innerhalb der neuen CSS-Regel, die Sie gerade erstellt haben, die folgende Zeile hinzu: `display: inline;`.

![](images/egMenuBarInline.png)

- Die Menüpunkte sind jetzt alle zusammen gequetscht, also fügen wir auch die Eigenschaften `margin-right` und `margin-left` um sie ein wenig auszublenden. Der CSS-Code-Block sollte jetzt so aussehen:

```css
    nav ul li {Liste-Stil-Typ: keine; Anzeige: Inline; Rand rechts: 10px; Rand links: 10px; }
```

Denken Sie daran: `10px` bedeutet zehn Pixel.

Wie wäre es damit, das Menü zu ändern, um Ihnen mitzuteilen, auf welcher Seite Sie sich befinden? Dieser Teil ist nicht im Stylesheet enthalten.

- Beginnen Sie mit der Startseite. Gehe zur Datei `index.html`. Entfernen Sie in der Liste der Menüverknüpfungen die Verknüpfungs-Tags vor und nach dem Wort `Home`, sodass das Listenelement für die Startseite nur Text zwischen `<li> </li>` Tags lautet, wie folgt: `<li>Home</li>`.

- Gehen Sie jetzt zu jeder Ihrer anderen Dateien und machen Sie dasselbe, jedes Mal, wenn Sie die Link-Tags für die zu bearbeitende Seite entfernen. So habe ich beispielsweise in der Datei `music.html` die Link-Tags im Listenfeld `Music`:

```html
    <header>
        <nav>
            <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="attractions.html">Orte zu besuchen</a></li>
            <li>Musik</li>
            <li><a href="food.html">Dinge zu essen</a></li>
            </ul>
        </nav>
    </header>
```

- Erkunden Sie Ihre Seiten, indem Sie auf die Links klicken. Sehen Sie, wie die Menüleiste die Seite, auf der Sie sich befinden, als reinen Text statt als Link anzeigt? 

![Beispiel einer Menüleiste, die die aktuelle Seite hervorhebt](images/egMenuBarOnPage.png)

Auf der nächsten Karte lernst du noch mehr CSS-Tricks, um die Menüleiste großartig aussehen zu lassen.