# README FOR NEW SITE

If you're a website developer you can read the [Quiqr Site Developer
Docs](https://book.quiqr.org/)
how to customize your Site Admin.

Quiqr is a Desktop App made for [Hugo](https://gohugo.io). Read all about
[creating Hugo websites](https://gohugo.io/getting-started/quick-start/).

To change this about text, edit this file: *C:\Users\Don-gigot\Quiqr\temp\siteFromDir\quiqr\home\index.md*.

Happy Creating.

# TODO :
- [ ] Implémenter [l'Image Processing](https://gohugo.io/content-management/image-processing/) de Hugo avec les [options srcset et webp](https://dev.to/jsco/a-comprehensive-guide-to-responsive-images-picture-srcset-source-etc-4adj) pour les images en utilisant les breakpoints du thème - voir le [page speed handbook](https://codestitch.app/page-speed-handbook)
- [ ] Créer une collection de documents de jeu
- [ ] Créer les collections/taxo de personnes, d'organisations
- [ ] Créer une collection de projets, de series, donner les champs correspondants aux posts
- [ ] Implémenter l'affichage en tête de post d'auteur·ices et dates (lastmod)
- [ ] Modifier le template baseof pour afficher correctement `menu_custom` plutôt que `menus.main`
- [ ] Créer les pages spéciales pour l'asso + collection documents admin
- [ ] Faire un tour de vérification des [Hugo Best Practices](https://github.com/spech66/hugo-best-practices?tab=readme-ov-file) et du [Front-End Checklist](https://github.com/thedaviddias/Front-End-Checklist), en particulier voir les `tag` de `head` (voir le template bexer ?)


## Issues :
- `select-from-query` crée un `null` quand on supprime son champ, ce qui empêche de rouvrir le formulaire. Facilement fixable (normalizeState -> toString)
- `easymde` a le curseur qui revient au tout début quand on tape pas très lentement. Voir [la doc du compo react encapsulé](https://www.npmjs.com/package/react-simplemde-editor) et [cet issue](https://github.com/RIP21/react-simplemde-editor/issues/116) ou pire [celui-ci](https://github.com/RIP21/react-simplemde-editor/issues/209) : manque un `useCallback` pour cacher la fonction de procès ?
- proposer d'ajouter (possiblement si flag) une option '' au select-from-query, facile en pushant dans les options
- proposer d'ajouter un flag facile pour avoir des collections de branch bundles (**_**index.html), en particulier pour des taxonomies et termes.
- Quiqr pas buildable, d'aucune manière : voir si la doc est à jour, sinon documenter mes essais

❤️ Quiqr