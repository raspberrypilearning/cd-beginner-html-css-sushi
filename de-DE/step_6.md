## Bilder hinzufügen

Lass uns ein Bild hinzufügen!

- Gehen Sie zur Registerkarte mit dem Namen `index.html`. Suchen Sie nach dem `</main>` -Tag und geben Sie die folgenden **über**: 

```html
    <img src="tito.png" alt="Tito the dog" width="100px" />
```

So sollte das Ergebnis aussehen:

![Bildcode und Bild von Tito](images/egImgCodeTito.png)

Beachten Sie, dass dieses Tag zusätzliche Informationen enthält. Sie werden **Attribute**.

- Suchen Sie das Bit mit dem Wert `width = "100px"` und versuchen Sie, mit verschiedenen Zahlen zu experimentieren, um zu sehen, ob Sie herausfinden können, was dieses Attribut bewirkt. Löschen Sie nicht die Buchstaben `px`!

\--- Einsturz \---

* * *

## titel: Wie funktioniert das `<img>` -Tag?

Beachten Sie, dass sich das `<img>` -Tag von den anderen Tags unterscheidet, die Sie bisher verwendet haben - es gibt kein abschließendes `</img>` -Tag. Stattdessen ist dieser Tag **selbstschließ**: Es hat `/>` am Ende. Dies liegt daran, dass für ein Bildelement kein Anfang und kein Ende vorhanden ist, wie es für Text auf der Seite der Fall ist.

Das Tag enthält **Attribute** mit zusätzlichen Informationen:

- Das Attribut `src` teilt dem Browser mit, welche Datei für das Bild verwendet werden soll. 
- Das Attribut `alt` ist eine kurze Beschreibung, die der Browser anzeigt, wenn das Bild nicht angezeigt werden kann. 'alt' ist die Abkürzung für 'alternativ'. Dieser Text hilft auch Leuten, die einen Bildschirmleser verwenden, um zu wissen, was das Bild ist.
- Das Attribut `width` teilt dem Browser mit, wie groß das Bild sein soll. `100px` bedeutet einhundert **Pixel**, das sind die kleinen Punkte, die das darstellen, was Sie auf Ihrem Bildschirm sehen. Wenn Sie dieses Attribut nicht angeben, wird das Bild in Originalgröße angezeigt.

\--- / einklappen \---

Nun, da Sie den Code kennen, um ein Bild auf Ihre Website zu setzen, möchten Sie wahrscheinlich das Bild ändern, richtig?

- Das erste, was Sie brauchen, ist natürlich ein Bild! Sie können entweder ein Foto verwenden, das Sie bereits auf Ihrem Computer haben, oder Sie können eines aus dem Internet erhalten.

[[[generic-get-picture-from-web]]]

**Hinweis:** nicht alle Bilder, die Sie im Internet finden, sind frei für jedermann zu benutzen. Wenn Sie ein Bild herunterladen, sollten Sie sicherstellen, dass es ein Bild ist, das Sie verwenden dürfen. Erfahren Sie mehr dazu hier:

[[[images-permissions-to-use]]]

Sobald Sie ein Bild haben, können Sie **Upload** die Datei zu Trinket:

- Klicke in deinem Schmuckstück auf das Symbol **Bild** neben dem **+** Zeichen. 

![Das Bildsymbol](images/tktImageIconArrow.png)

Hier können Sie die Bilder sehen, die Sie auf Ihrer Website verwenden können. Sie sollten das Bild von Tito, dem CoderDojo-Hund, sehen.

- Klicken Sie auf die Schaltfläche **Bild** hinzufügen und anschließend auf **Hochladen**.

- Klicken Sie auf die Schaltfläche **Klicken Sie auf Dateien auswählen**. Suchen und doppelklicken Sie in dem sich öffnenden Fenster auf Ihre Bilddatei.

- Klicken Sie auf **Fertig**.

![Bild-Upload-Bereich](images/tktUploadImages.png)

Ihr Bild wird hochgeladen und sollte einsatzbereit sein.

- Gehe zur Datei `index.html` und finde das `<img>` Tag. Ändern Sie den Text `tito.png` so, dass er exakt mit dem Namen der ausgewählten Bilddatei übereinstimmt. Beachten Sie, dass der Name möglicherweise in `.jpg` statt in `.png`endet!

Der gerade geänderte Text ist das Attribut `src`, das dem Browser mitteilt, welche Datei angezeigt werden soll.

**Hinweis:** Der Wert, den Sie für ein Attribut eingeben, muss in Anführungszeichen `""`!

\--- Herausforderung \---

## Herausforderung: Ändere den Alt-Text des Bildes

- Suchen Sie das Attribut `alt` Ihres Bildelements und ändern Sie den darin enthaltenen Text in eine kurze Beschreibung Ihres Bildes. 

\--- /Herausforderung \---