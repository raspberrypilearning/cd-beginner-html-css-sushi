## Styling der Menüleiste

Mit CSS sind die Möglichkeiten, Ihre Menüleiste großartig zu gestalten, endlos.

- Gehe wieder zur `styles.css` Datei - der Ort, an dem die coolen Sachen passieren!

- Suchen Sie Ihren `nav ul` Selektor und fügen Sie weitere Regeln hinzu, damit er so aussieht:

```css
  nav ul {Hintergrundfarbe: Tomate; Rand-Stil: fest; Randfarbe: MediumVioletRed; Rahmenbreite: 2px; Auffüllen: 10px; }
```

Die Eigenschaft `padding` fügt Speicherplatz hinzu. Können Sie herausfinden, was jede andere Eigenschaft tut? Experimentieren Sie mit verschiedenen Farben und Pixelzahlen.

![Menüleiste mit Rahmen und Füllung hinzugefügt](images/egMenuBarMoreStyle.png)

- Um die Unterstreichung der Links zu entfernen, fügen Sie den folgenden Code in einer neuen Zeile nach der schließenden geschweiften Klammer `}` für die `nav ul li` -Regeln hinzu. Du könntest es nach jeder `}`, aber es ist eine gute Idee, verwandte Sachen zusammen zu halten, damit es leichter zu finden ist!

```css
  nav ul li a {Textdekoration: keine; }
```

Die obige Regel gilt für Links `<a>` innerhalb von Listenelementen `<li>` in einer ungeordneten Liste `<ul>` innerhalb eines Navigationsabschnitts `<nav>`. Wow, das sind vier Selektoren!

![Menüleiste mit unterstrichener Verknüpfung entfernt](images/egMenuBarNoUnderline.png)

Denken Sie daran, wie Sie die Link-Tags aus einigen Listenelementen in der `<nav>` damit Sie leicht sehen können, auf welcher Seite Sie sich gerade befinden. Warum ändern Sie nicht auch die Textfarbe der Navigationslistenelemente, die keine Links sind!

- Suchen Sie Ihren `nav ul li` Selektor und **innerhalb von** fügen Sie die geschweiften Klammern die Zeile hinzu:

```css
  Farbe: PapayaWhip;
```

Sie können jede mögliche Farbe wählen, die Sie mögen!

Sie können der Eigenschaft `nav ul li a` Eigenschaft `color` hinzufügen, wenn die Menüverknüpfungen eine andere Farbe haben sollen als die anderen Links auf Ihrer Website.

- Wie wäre es mit einigen abgerundeten Ecken für Ihr Menü? Versuchen Sie, der Regel `nav ul` den folgenden Code hinzuzufügen, um zu sehen, was passiert: `border-radius: 10px;`.

Die Eigenschaft `border-radius` ist eine wirklich einfache Möglichkeit, alles cooler aussehen zu lassen!

![Webseite mit abgerundeten Ecken in der Menüleiste und auf einem Bild](images/egMenuBarFullStyles_result.png)

\--- Herausforderung \---

## Herausforderung: Machen Sie aus Ihren Bildern abgerundete Ecken

- Erstellen Sie in Ihrem Stylesheet mit dem Selektor `img` einen neuen Regelsatz für Bilder, und fügen Sie dort eine Regel `border-radius`.

\--- /Herausforderung \---