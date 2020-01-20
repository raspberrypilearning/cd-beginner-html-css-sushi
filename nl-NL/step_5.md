## Afbeeldingen toevoegen

Laten we een afbeelding toevoegen!

- Ga naar het tabblad met de naam `index.html`. Vind de `</main>` tag en typ het volgende **daarboven**: 

```html
    <img src="tito.png" alt="Tito the dog" width="100px" />
```

Hier is hoe het resultaat eruit zou moeten zien:

![Image code and picture of Tito](images/egImgCodeTito.png)

Merk op dat deze tag extra stukjes informatie bevat. Ze worden **attributes** (attributen) genoemd.

- Zoek het stukje code met `width = "100px"` en probeer te experimenteren met verschillende getallen om te zien of je kunt achterhalen wat dit attribute doet. Verwijder niet de letters `px`!

## \--- collapse \---

## title: How the `img` tag works

Notice that the `<img>` tag is different from the other tags you've used so far — there is no closing `</img>` tag. Instead, this tag is **self-closing**: it has `/>` at the end. This is because there is no 'start' and 'end' to an image element like there is for text on the page.

The tag contains **attributes** with extra information:

- Het `src` attribuut vertelt de browser welk bestand moet worden gebruikt voor de afbeelding. 
- Het `alt` attribute is een korte beschrijving die de browser zal weergeven als het de afbeelding niet kan weergeven. 'alt' is een afkorting voor 'alternatief'. Deze tekst helpt ook mensen die een schermlezer gebruiken om te weten wat de afbeelding weergeeft.
- Het `width` attribuut vertelt de browser hoe breed het de afbeelding moet weergeven. `100px` betekent honderd **pixels**, dat zijn de kleine puntjes die bepalen wat je op je scherm ziet. Als je dit kenmerk niet opneemt, wordt de afbeelding in de oorspronkelijke grootte weergegeven.

\--- /collapse \---

Now that you know the code to put a picture on your website, you probably want to change the picture, right?

- Het eerste dat je nodig hebt is natuurlijk een afbeelding of foto! Je kunt er een gebruiken die je al op je computer hebt staan, zoals een foto die je hebt gemaakt, of je kunt er een downloaden van internet.

[[[generic-get-picture-from-web]]]

**Note:** not all images you will find on the internet are free for anyone to use. If you download a picture, you should make sure it is one that you are allowed to use. Find out more about this here:

[[[images-permissions-to-use]]]

Once you have a picture, you can **upload** the file to Trinket:

- Klik in je trinket op het **image** pictogram naast het **+** teken. 

![The image icon](images/tktImageIconArrow.png)

This is where you can see the pictures that you are able to use on your website. You should see the picture of Tito, the CoderDojo dog.

- Klik op de knop **Add Image** en klik vervolgens op **Upload**.

- Klik op de knop **Click To Select Files**. Zoek en dubbelklik op je afbeelding in het venster dat wordt geopend.

- Klik op **Done**.

![Image upload area](images/tktUploadImages.png)

Your picture will be uploaded and should be ready to use.

- Ga naar het bestand `index.html` en zoek de `<img>` tag. Wijzig de tekst `tito.png` zodat het precies overeenkomt met de naam van de afbeelding die je hebt gekozen. Merk op dat de naam eindigt op `.jpg` in plaats van `.png`!

The text you just changed is the attribute called `src`, which tells the browser which file to display.

**Note:** the value you type for an attribute must have quotation marks `""` around it!

\--- challenge \---

## Challenge: change the alt text of the picture

- Zoek het `alt` attribuut van je afbeelding en verander de tekst daarvan in een korte beschrijving van je afbeelding. 

\--- /challenge \---