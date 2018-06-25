## Ajouter plus de pages

Cette carte vous montrera comment ajouter plus de pages à votre site Web.

- En haut du panneau de code, cliquez sur le symbole **+** côté des onglets et tapez un nom pour votre nouveau fichier. Il doit se terminer par `.html` (y compris le point!) Afin que le navigateur sache qu'il s'agit d'une page Web.

![Ajout d'un nouveau fichier dans Trinket](images/tktNewFileArrows.png)

## \--- effondrer \---

## title: Renommer ou supprimer un fichier

Si vous voulez changer le nom d'un fichier, cliquez sur l'icône **cog** à droite du nom du fichier, puis sur l'icône **crayon**. Tapez le nouveau nom et appuyez sur **Entrez**. Vous pouvez également supprimer un fichier en cliquant sur l'icône **bin** au lieu de l'icône **crayon**. ![](images/EditFilename.png)

Vous pourriez vous demander pourquoi vous ne pouvez pas changer le nom du fichier `index.html`. `index.html` est un nom spécial utilisé pour la **page d' accueil** d'un site Web. C'est la première page sur laquelle vous arrivez lorsque vous visitez un site Web. Chaque fois que vous allez à la page d'accueil d'un site Web, le navigateur recherche le fichier appelé `index.html` et l'affiche sur votre écran.

\--- /effondrer \---

- Trouvez le fichier `blank_page.html` et copiez et collez tout le code de celui-ci dans votre nouveau fichier. Puisque vous voulez copier le tout, vous pouvez cliquer n'importe où sur le code et utiliser le raccourci clavier <kbd>Ctrl</kbd> (ou <kbd>cmd</kbd>) et <kbd>A</kbd> pour tout sélectionner à la fois.

- Changez le texte entre les balises `<title> </title>` afin que votre nouvelle page ait un titre approprié. Le bijou n'affichera pas le titre, mais vous pouvez le voir en haut de la fenêtre de votre navigateur si vous téléchargez votre projet.

![Le titre de la page affiché dans l'onglet du navigateur](images/egLocalFileWindowTitle.png)

- Entre les balises `<main> </main>` du nouveau fichier, utilisez les balises que vous avez apprises pour ajouter des éléments à la page, tels que des paragraphes, des en-têtes, des images et des listes!

- Répétez les étapes ci-dessus pour chaque nouvelle page que vous souhaitez ajouter.

Quand il y a trop d'onglets pour que Trinket apparaisse en même temps, vous pouvez utiliser les icônes **<** et **>** dans le coin supérieur gauche des onglets pour les faire défiler.

![Les boutons pour faire défiler les onglets](images/tktScrollTabIcons.png)

Maintenant, vous devez faire des liens pour que vous puissiez accéder à chacune de vos nouvelles pages! Mettons tous les liens dans une liste.

- Dans le fichier `index.html` , ajoutez le code suivant au corps de votre page Web:

```html
    <ul>
        <li><a href="index.html">Accueil</a></li>
        <li><a href="attractions.html">Endroits à visiter</a></li>
        <li><a href="music.html">Musique</a></li>
        <li><a href="food.html">Choses à manger</a></li>
    </ul>
```

- Changez la valeur de l'attribut `href` pour chaque lien (souvenez-vous, c'est le texte à l'intérieur des guillemets) afin qu'il corresponde exactement au nom de chaque fichier HTML que vous avez créé.

- Changez le texte entre les balises `<a> </a>` en descriptions appropriées de vos pages.

Vous pouvez maintenant naviguer vers vos nouvelles pages!

![Exemple de liste de liens sur une page Web](images/egListOfPageLinks.png)