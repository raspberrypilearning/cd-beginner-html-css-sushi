## Erstellen von Links

Auf dieser Karte erfahren Sie, wie Sie einen Link erstellen, der Sie zu einer anderen Seite führt, wenn Sie darauf klicken.

- Fügen Sie dem Hauptteil von `index.html`den folgenden Code hinzu:

```html
  <a href="">Klicken Sie hier</a>
```

Die `<a> </a>` -Tags verwandeln alles, was dazwischen ist, in einen Link.

- Versuchen Sie, auf Ihren Link zu klicken, um zu sehen, was passiert. Es tut nichts, oder?

Das liegt daran, dass das Attribut `href` im Moment leer ist. Es muss die **URL** (Webadresse) der Seite enthalten, auf die Sie verlinken möchten.

- Gehe zu Wikipedia und finde eine Seite über etwas auf deiner Webseite. Ich werde die Seite über Irland benutzen.

- Klicken Sie in die Adressleiste und wählen Sie den gesamten Text in i5 aus. Das ist die vollständige URL der Seite, auf der Sie sich befinden. Drücken Sie die Taste <kdb>Strg</kdb> (oder <kdb>cmd</kdb>) und <kdb>C</kdb> Tasten gleichzeitig um es zu kopieren.
    
    ![URL in der Adressleiste](images/AddressBarURL.png)

- Klicken Sie in Ihrem Schmuckstück zwischen die Anführungszeichen nach `href =` und drücken Sie die <kdb>Strg</kdb> (oder <kdb>cmd</kdb>) und <kdb>V</kdb> gleichzeitig die Taste drücken, um die URL, die Sie gerade kopiert haben, einzufügen. Ihr Code sollte nun ungefähr so ​​aussehen:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">Klicken Sie hier</a>
```

Du hast gerade deinen ersten Link erstellt! Klicken Sie darauf, um zu sehen, ob es jetzt funktioniert.

![Link-Tag](images/egLinkTagWithURL.png)

## \--- Einsturz \---

## Titel: Links zu anderen Websites

Trinket hat Probleme mit einigen Webadressen. Sie können URLs von anderen Websites als Wikipedia ausprobieren, wenn Sie möchten, aber sie funktionieren möglicherweise nicht in Ihrem Schmuckstück. Wenn Sie jedoch Ihr Projekt herunterladen und die Dateien in einem Webbrowser anzeigen würden, würden die Links funktionieren.

\--- / einklappen \---

- Versuchen Sie ein Bild zwischen den `<a> </a>` Tags anstelle der Wörter `Klicken Sie hier`, so:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">
      <img src="tito.png" alt="Tito the dog" width="100px" />
  </a>
```

- Klicken Sie auf Ihr Bild. Siehst du, dass es zu einem Link wurde?

Sie können einen Link auch in andere Elemente Ihrer Webseite einfügen, z. B. in einen Absatz oder sogar in eine Liste. Hier ist ein Beispiel für einen Satz mit einem Link darin:

```html
  <p>
    <a href="https://en.wikipedia.org/wiki/Ireland">Klicken Sie hier</a> , um die Wikipedia-Seite zu lesen!
  </p>
```

\--- Herausforderung \---

## Herausforderung: Fügen Sie einen Link in eine Liste ein

- Sehen Sie, ob Sie eine Liste mit einem Link in einem der Listenelemente erstellen können.

\--- /Herausforderung \---