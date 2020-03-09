## Navigation de ton site web

De nombreux sites web ont un menu **navigation** pour aider les visiteurs à se déplacer entre les pages. Maintenant que tu as un tas de pages, une page d'accueil et des liens vers chaque page, déplaçons la liste des liens vers une section de navigation en haut de chaque page.

![Exemple d'une page web avec des liens de navigation en haut](images/egNavLinksAtTop.png)

- Trouve le code de ta liste de liens que tu as créé dans l'étape précédente.

- Juste avant la balise d'ouverture `<ul>`, appuie sur **Entrer** pour créer une nouvelle ligne vierge, puis sur le nouveau type de ligne de la balise suivante: `<nav>`. Trinket ajoute automatiquement la balise de fermeture juste après, mais tu peux la supprimer — ce n'est pas au bon endroit.

- Juste **après** la balise de fermeture `</ul>`, appuie sur **Entrer** pour créer une nouvelle ligne vierge, et tape dans la balise de fermeture `</nav>` juste à cet endroit là.

- Maintenant, sélectionne la section entière `<nav>` et la liste en cliquant juste avant l'ouverture de la balise `<nav>` et en faisant glisser la souris jusqu'à la fin de la balise `</nav>` pour que tout le texte, y compris les balises d'ouverture et de fermeture, soit mis en évidence. Assure-toi que tout les **crochets** `<` et `>` au début et à la fin soient également surlignés!

![Le texte à gauche n'est pas entièrement sélectionné lorsque le texte à droite l'est](images/egSelectedYayWoops.png)

- Tu vas **couper** cette fois au lieu de copier. Maintiens la touche <kbd>Ctrl</kbd> (ou <kbd>cmd</kbd>) et tout en la maintenant, appuie sur la touche <kbd>X</kbd>. Le code en surbrillance disparaîtra, mais ne panique pas!

- En haut du fichier, clique dans l'espace entre les balises `<header> </header>` . Assure-toi de voir le curseur clignoter à cet endroit. Colle maintenant le code en appuyant <kbd>Ctrl</kbd> (ou <kbd>cmd</kbd>) et <kbd>V</kbd> comme d'habitude. Le code devrait ressembler à ceci:

```html
    <header>
        <nav>
            <ul>
            <li><a href="index.html">Accueil</a></li>
            <li><a href="attractions.html">Lieux à visiter</a></li>
            <li><a href="music.html">Musique</a></li>
            <li><a href="food.html">Choses à manger</a></li>
            </ul>
        </nav>
    </header>
```

--- collapse ---
---
title: Annuler!
---

Si tu commets une erreur, tu peux **annuler** en appuyant sur <kbd>Ctrl</kbd> (ou <kbd>cmd</kbd>) et <kbd>Z</kbd> ensemble. Tu peux généralement appuyer sur cette combinaison de touches à plusieurs reprises pour annuler les dernières modifications. Il s'agit d'un autre raccourci clavier pratique que tu peux utiliser dans de nombreux programmes!

--- /collapse ---

- Essaie tes liens pour s'assurer qu'ils fonctionnent toujours.

--- challenge ---

## Défi: menus de navigation pour toutes les pages

- Mets cette section de code dans la section en-tête de chaque fichier HTML que tu as créé. Cela fera apparaître le menu de navigation en haut de chaque page de ton site web.
    
--- hints ---

    
--- hint ---

Sélectionne la section entière `<nav>` comme tu l'as fait auparavant, et appuie simultanément sur les touches <kbd>Ctrl</kbd> (ou <kbd>cmd</kbd>) et <kbd>C</kbd> pour la copier.

Ensuite, dans chacun de tes fichiers `.html` , clique dans la section `<header> </header>` et colle le code exactement comme tu l'as fait précédemment.

--- /hint ---

--- /hints ---

Tu peux maintenant cliquer sur les liens, peu importe la page sur laquelle tu te trouves.

--- /challenge ---