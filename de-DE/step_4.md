## Steuern wie es aussieht

Der Code, der beschreibt, wie eine Website aussieht, heißt **CSS**.

- Sehe Dir die Tabs oben im Codebereich an und öffne die Datei `styles.css`, indem du auf den Reiter mit diesem Namen klickst. Die Datei enthält den folgenden Text:

```css
  body {
      background-color: white;
  }
```

- Ändere die Farbe `white` ("weiß") zu `LightSkyBlue`("helles Himmelblau") und schau was passiert. Deine Website sollte jetzt einen blauen Hintergrund haben! 

![Beispiel mit blauem Hintergrund](images/egFirstCSSbluebg.png)

--- collapse ---
---
title: Wie funktioniert es?
---

Wenn du den Anfang der Datei `index.html` ansiehst, findest du folgende Zeile:

```html
  <link type="text/css" rel="stylesheet" href="styles.css"/>
```

Die obige Zeile weist den Browser an, nach einer speziellen Datei namens `styles.css` zu suchen. Diese spezielle Datei wird ein **Stylesheet** genannt. Du erkennst eine Stylesheet-Datei an der `.css` Endung im Namen.

Ein Stylesheet enthält **Regeln** für das Aussehen jedes Elements auf deiner Webseite.

Die geschweiften Klammern `{ }` und der Code dazwischen sind ein Satz **CSS-Regeln**. Das Wort `body` bedeutet, dass die Regeln für alle `<body>` (also "Hauptteil-") Elemente auf deiner Website gelten. Wir nennen das Teil vor den geschweiften Klammern einen **Selector**. In diesem Fall ist es der Selektor für die body-Elemente.

Jede Regel in den geschweiften Klammern besteht aus:

- Einer **Eigenschaft** auf der linken Seite, gefolgt von einem Doppelpunkt-symbol `:`
- Einen **Wert** für die Eigenschaft auf der rechten Seite nach dem Doppelpunkt
- Ein Semikolon-Symbol `; ` am Ende

--- /collapse ---

- Lass uns jetzt Regeln hinzufügen, um das Aussehen des Textes anzupassen. Füge zwei neue Zeilen zwischen die geschweiften Klammern ein:

```css
  body {
    background-color: LightSkyBlue;
    font-family: "Helvetica", sans-serif;
    color: purple;
  }
```

Schau, wie das die Website verändert hat.

Die Eigenschaft `color` ist immer für Text. Hier legst du die Farbe für den gesamten Text im `body` von deiner Webseite fest.

- Du kannst auch separate Regeln für die Überschriften und Absätze definieren. Für `<h1>` Überschriften verwendest du den `h1` Selektor. Füge folgenden Code unter der schließenden geschweiften Klammer der body-Regel hinzu.

```css
  h1 {
    color: orange;
    font-family: "Times New Roman", serif;
  }
```

Der Überschriften-Text sollte jetzt orange sein und der Absatz noch lila.

![Ergebnis des neuen CSS-Codes](images/egCssColorsFonts.png)

Hast du bemerkt, wie die Buchstaben auch anders aussehen und eine andere Farbe haben? Dies liegt daran, dass du ihre **font family** (d.h. Schriftart) geändert hast. [Hier](http://dojo.soy/web-font-families) findest du weitere Schriftarten.

- Versuche einen Satz Regeln für die `<h2>` Überschriften hinzuzufügen, indem du den `h2` Selektor verwendest.

- Du könntest verschiedene Farbkombinationen für Text und Hintergrund ausprobieren. Viele Farben stehen zur Verfügung. Du findest eine vollständige Liste von ihnen [hier](http://dojo.soy/web-color-names).