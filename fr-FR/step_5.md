## Ajout d'images

Ajoutons une image !

- Va sur l'onglet nommé `index.html` . Trouve la balise `</main>` et tape ce qui suit **au dessus** : 

```html
    <img src="tito.png" alt="Tito the dog" width="100px" />
```

Voici à quoi devrait ressembler le résultat:

![Code d'image et image de Tito](images/egImgCodeTito.png)

Note que cette balise contient des informations supplémentaires. Ils sont appelés **attributs**.

- Trouve le morceau de code qui dit `width="100px"` et essaie d'expérimenter avec des nombres différents pour voir si tu peux déterminer ce que fait cet attribut. Ne supprime pas les lettres `px`!

## \--- collapse \---

## title: How the `img` tag works

Notice that the `<img>` tag is different from the other tags you've used so far — there is no closing `</img>` tag. Instead, this tag is **self-closing**: it has `/>` at the end. This is because there is no 'start' and 'end' to an image element like there is for text on the page.

The tag contains **attributes** with extra information:

- L'attribut `src` indique au navigateur quel fichier utiliser pour l'image. 
- L'attribut `alt` est une courte description que le navigateur montrera s'il ne peut afficher l'image. «alt» est l'abréviation de «alternative». Ce texte aide également les personnes utilisant un lecteur d'écran à savoir quelle est l'image.
- L'attribut ` width` indique au navigateur la largeur de la photo. `100px` signifie une centaine de **pixels**, qui sont les petits points qui composent ce que tu vois sur ton écran. Si tu n'inclus pas cet attribut, l'image sera affichée dans sa taille d'origine.

\--- /collapse \---

Now that you know the code to put a picture on your website, you probably want to change the picture, right?

- La première chose dont tu auras besoin est bien sûr d'une image! Tu peux soit utiliser une que tu as déjà sur ton ordinateur, comme une photo que tu as prise, soit tu peux en obtenir une sur Internet.

[[[generic-get-picture-from-web]]]

**Note:** not all images you will find on the internet are free for anyone to use. If you download a picture, you should make sure it is one that you are allowed to use. Find out more about this here:

[[[images-permissions-to-use]]]

Once you have a picture, you can **upload** the file to Trinket:

- Dans ton trinket, clique sur l'icône **image** à côté du signe **+** . 

![The image icon](images/tktImageIconArrow.png)

This is where you can see the pictures that you are able to use on your website. You should see the picture of Tito, the CoderDojo dog.

- Clique sur le bouton **Ajouter une image** puis clique **Télécharger**.

- Clique sur le bouton **Cliquez pour sélectionner des fichiers**. Trouve et double-clique sur ton fichier d'image dans la fenêtre qui s'ouvre.

- Clique **Terminé**.

![Image upload area](images/tktUploadImages.png)

Your picture will be uploaded and should be ready to use.

- Va dans le fichier `index.html` et trouve la balise `<img>`. Change le texte `tito.png` pour qu'il corresponde exactement au nom du fichier image que tu as choisi. Note que son nom peut se terminer par `.jpg` au lieu de `.png` !

The text you just changed is the attribute called `src`, which tells the browser which file to display.

**Note:** the value you type for an attribute must have quotation marks `""` around it!

\--- challenge \---

## Challenge: change the alt text of the picture

- Trouve l'attribut ` alt ` de ton élément d’image et change le texte en une brève description de ton image. 

\--- /challenge \---