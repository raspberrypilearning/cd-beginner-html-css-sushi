## Deine erste Website!

- Klicke auf der linken Seite, dem **code Bereich**, auf den Reiter `index.html`.

- Finde die Zeile, `Willkommen in Irland!` und ändere diese in deine eigene Nachricht — achte darauf, dass du die Tags `<p>` am Anfang der Zeile und `</p>` am Ende der Zeile **nicht** löschst. Deine Website sollte sich auf der rechten Seite entsprechend aktualisieren.

![HTML Absatz Beispiel](images/egFirstHtmlCode.png)

- Ändere nun in derselben Zeile die Werte `<p>` und `</p>` bis `<h1>` und `</h1>`. Siehst du eine Änderung im Ergebnis auf der rechten Seite?

```html
  <h1>Willkommen in Irland!</h1>
```

--- collapse ---
---
title: HTML und Tags erklärt
---

**HTML** ist der Code, der eine Webseite generiert.

Das `.html` im Dateinamen teilt dem Browser mit, dass die Datei eine Webseite ist, sodass der Browser weiß, dass er nach **Tags** suchen soll, die ihm sagen, was er anzeigen soll. (Ein Browser ist das Programm, mit dem du Websites aufrufst, zum Beispiel Chrome oder Firefox.)

HTML-Tags wie `<p>` und `</p>` definieren verschiedene Teile einer Seite, zum Beispiel Absätze, Überschriften oder Hauptteil. Die Teile werden **Elemente** genannt. Betrachte sie als Bausteine.

### Warum brauche ich zwei Tags?

Du brauchst einen **öffnenden** und einen **schließenden** Tag, um dem Browser mitzuteilen, wo das Element **startet** und **endet**. Also für einen Absatz, sagt der öffnende `<p>` Tag "Hier kommt ein Text und der soll als Absatz angezeigt werden." Der schließende `</p>` Tag teilt dem Browser mit, wo der Absatz endet.

Alles zwischen den `<body>` und `</body>` Tags ist deine Webseite.

- Beachte, dass der schließende Tag **immer** einen Schrägstrich `/` hat.

--- /collapse---

- Versuche die Zahlen in den **Überschrift** Tags zu ändern, um zu sehen, wie sich die Größe verändert. Sie können von `<h1>` bis `<h6>` gehen. Denke daran, sowohl den öffnenden als auch den schließenden Tag zu ändern, damit sie übereinstimmen.

- Finde den Code für den Absatz, der lautet `Meine Website geht um Irland.` und passe ihn so an:

```html
  <p>
 <em>Meine Webseite</em> geht um <strong>Irland</strong>. 
    Sie enthält folgende Seiten: Attraktionen, Musik, Essen
 </p>
```

Findest du heraus, was die `<em></em>` und `<strong></strong>`Tags bewirken?

![Beispiel von HTML Tags](images/egFirstTags.png)

--- challenge ---

## Herausforderung: Füge deinen eigenen Text hinzu

- Füge deiner Seite einen neuen Absatz oder eine neue Überschrift hinzu, indem du einige der Tags verwendest, die du kennengelernt hast.

--- hints ---


--- hint --- Wenn du einen Text auf einer Seite platzieren möchtest, musst du ihn zwischen zwei Tags setzen, die dem Browser mitteilen, wie er den Text anzeigen soll. Zum Beispiel teilen die `<p> </p>` Tags dem Browser mit, dass alles, was zwischen ihnen ist, ein neuer Absatz ist, und die `<h1> </h1>` Tags, dass der Text eine Überschrift ist.

--- /hint ---

--- hint ---

Der Code für Absätze sieht so aus:

```html
  <p>Dies ist ein Absatz.</p>
 <p>Dies ist ein weiterer Absatz.
  Alles zwischen zwei p-Tags wird 
  in einer langen Zeile auf der Webseite angezeigt. </p>
```

--- /hint ---

--- hint ---

Der Code für Überschriften sieht so aus:

```html
  <h1>Dies ist eine Überschrift.</h1>
```

Überschriften werden normalerweise größer oder fetter als Absätze angezeigt.

--- /hint ---

---/hints---

---/ challenge ---

Herzlichen Glückwunsch, du hast deine erste Webseite erstellt! Auf der nächsten Karte lernst du, wie du das Aussehen kontrollieren kannst.