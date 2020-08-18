## Aggiungere più pagine

Questa scheda ti mostrerà come aggiungere più pagine al tuo sito web.

- Nella parte superiore del pannello del codice, fai clic sul simbolo **+** accanto alle schede e digita un nome per il tuo nuovo file. Deve terminare in `.html` (incluso il punto!) in modo che il browser sappia che si tratta di una pagina web.

![Aggiungere un nuovo file in Trinket](images/tktNewFileArrows.png)

--- collapse ---
---
title: Rinominare ed eliminare un file
---

Se si desidera modificare il nome di un file, fai clic sull'icona **ingranaggio** a destra del nome del file, quindi fai clic sull'icona **matita**. Digitare il nuovo nome e premi **Invio**. Puoi anche eliminare un file facendo clic sull'icona **cestino** invece che sull'icona **matita**.

![](images/EditFilename.png)

Ci si potrebbe chiedere perché non è possibile modificare il nome del file `index.html`. `index.html` è un nome speciale utilizzato per la **homepage** di un sito Web. Questa è la prima pagina sulla quale ti trovi quando visiti un sito web. Ogni volta che si accede alla home page di un sito web, il browser cerca il file denominato `index.html` e lo visualizza sullo schermo.

--- /collapse ---

- Trova il file `blank_page.html` e copia e incolla tutto il codice contenuto in esso nel nuovo file. Volendo copiare tutto, puoi fare clic in qualsiasi punto del codice e utilizzare la scorciatoia da tastiera <kbd>Ctrl</kbd> (o <kbd>cmd</kbd>) e <kbd>A</kbd> per selezionarla in una volta sola.

- Cambia il testo tra i tag `<title> </title>` in modo che la tua nuova pagina abbia un titolo migliore. Trinket non visualizzerà il titolo, ma puoi vederlo nella parte superiore della finestra del browser se scarichi il tuo progetto.

![Il titolo della pagina visualizzato nella scheda del browser](images/egLocalFileWindowTitle.png)

- All'interno dei tag `<main> </main>` del nuovo file, usa i tag che hai imparato per aggiungere elementi alla pagina, come paragrafi, intestazioni, immagini ed elenchi!

- Ripeti i passaggi precedenti per ogni nuova pagina che vuoi aggiungere.

Quando ci sono troppe schede da visualizzare in Trinket, puoi usare le icone **<** e **>** nell'angolo in alto a sinistra delle schede per scorrere tra di esse.

![I pulsanti per scorrere le schede](images/tktScrollTabIcons.png)

Ora devi creare collegamenti in modo da poter accedere a ciascuna delle tue nuove pagine! Mettiamo tutti i link in una lista.

- Nel file `index.html`, aggiungi il seguente codice al corpo della tua pagina web:

```html
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="attractions.html">Luoghi da visitare</a></li>
        <li><a href="music.html">Musica</a></li>
        <li><a href="food.html">Cose da mangiare</a></li>
    </ul>
```

- Cambia il valore dell'attributo `href` per ogni link (ricorda, questo è il testo tra virgolette) in modo che corrisponda esattamente al nome di ogni file HTML che hai creato.

- Cambia il testo tra i tag `<a> </a>` e le descrizioni appropriate delle tue pagine.

Ora puoi navigare verso le tue nuove pagine!

![Esempio di lista di collegamenti su una pagina web](images/egListOfPageLinks.png)