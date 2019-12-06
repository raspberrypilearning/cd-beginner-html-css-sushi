## Bilder hinzufügen

Fügen wir ein Bild hinzu!

- Klicke auf den Reiter `index.html`. Suche nach dem `</main>` -Tag und gib folgendes **in der Zeile darüber** ein: 

```html
    <img src="tito.png" alt="Tito the dog" width="100px" />
```

So sollte das Ergebnis aussehen:

![Bildcode und Bild von Tito](images/egImgCodeTito.png)

Beachte jedoch, dass dieses Tag zusätzliche Informationen enthält. Diese werden **Attribute** genannt.

- Finde das Codestück `width="100px"` und probiere verschiedene Zahlen aus, um herauszufinden, was dieses Attribut tut. Lösche dabei die Buchstaben `px` nicht!

--- collapse ---

* * *

## title: Wie das `img` Tag funktioniert

Beachte, dass das `<img>` Tag anders ist, wie die anderen Tags, die du bisher verwendet hast — es hat kein schließendes `</img>` Tag. Stattdessen ist dieses Tag **selbstschließend**: Es hat `/>` am Ende. Das liegt daran, dass es kein 'Start' und 'Ende' für ein Bildelement gibt, wie es für Text gibt.

Das Tag enthält **Attribute** mit zusätzlichen Informationen:

- Das `src`-Attribut teilt dem Browser mit, welche Datei er für das Bild verwenden soll. 
- Das `alt`-Attribut ist eine kurze Beschreibung, die der Browser anzeigt, wenn das Bild nicht angezeigt werden kann. 'alt' ist kurz für 'Alternative'. Dieser Text wird auch von einem Bildschirmleser verwendet, damit Sehbehinderte wissen, was das Bild darstellt.
- Das `width` Attribut teilt dem Browser mit, wie breit das Bild sein soll. `100px` bedeutet einhundert **Pixel**, das sind die winzigen Punkte, die das Bild auf deinem Bildschirm formen. Wenn du dieses Attribut nicht angibst, wird das Bild in seiner Originalgröße angezeigt.

--- /collapse ---

Da du den Code jetzt kennst, um ein Bild auf deine Website zu platzieren, möchtest du das Bild sicherlich ändern, oder?

- Das erste, was du brauchst, ist natürlich ein Bild! Du kannst entweder ein Bild verwenden, das bereits auf deinem Computer ist, wie z.B. ein von dir erstelltes Foto. Du kannst aber auch einfach eines aus dem Internet einfügen.

[[[generic-get-picture-from-web]]]

**Achtung:** Nicht alle Bilder, die du im Internet findest, sind frei nutzbar. Wenn du ein Bild herunterlädst, solltest du sicherstellen, dass es ein Bild ist, das du verwenden darfst. Erfahre mehr dazu hier:

[[[images-permissions-to-use]]]

Sobald du ein Bild hast, kannst du es zu Trinket **hochladen**:

- Klicke in Trinket auf das **Bild**-Symbol neben dem **+** Zeichen. 

![Das image Symbol](images/tktImageIconArrow.png)

Hier kannst du die Bilder sehen, die du auf deiner Website verwenden kannst. Du solltest das Bild von Tito, dem CoderDojo Hund, sehen.

- Klicke die **Add image** Schaltfläche und dann klicke **Upload**.

- Klicke auf die Schaltfläche **Click to select files** (Dateien auswählen). Finde und doppel-klicke auf deine Bilddatei in dem Fenster, das sich öffnet.

- Klicke **Done** (fertig).

![Bild-Upload-Bereich](images/tktUploadImages.png)

Dein Bild wird hochgeladen und sollte einsatzbereit sein.

- Gehe zur Datei `index.html` und finde den `<img>` Tag. Ändere den Text `tito.png` so, dass er exakt mit dem Namen der von dir ausgewählten Bilddatei übereinstimmt. Beachte, dass der Name möglicherweise auf `.jpg` anstelle von `.png` endet!

Du hast gerade das Attribut `src` geändert, das dem Browser mitteilt, welche Datei angezeigt werden soll.

**Achtung:** Der Wert, den du für ein Attribut eingibst, muss in Anführungszeichen `""` stehen!

--- challenge ---

## Herausforderung: Ändere den alt-Text des Bildes

- Suche das Attribut `alt` deines Bildelements und ändere den darin enthaltenen Text zu einer kurzen Beschreibung deines Bildes. 

--- /challenge ---