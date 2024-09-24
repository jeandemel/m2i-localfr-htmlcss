# Formation HTML/CSS

Dépôt avec les exercices et exemples pour la formation HTML/CSS de septembre 2024


## Structures [html](first.html)
Quelques exemples de balises HTML. Pour avoir une liste documentée à jour, [la doc de mozilla](https://developer.mozilla.org/fr/docs/Web/HTML/Element) est très bien.

À retenir surtout, on utilise le HTML pour structurer nos documents, structurer de manière logique pour indiquer aux lecteurs d'écrans, aux robots ou autre, ce que représentent les différents blocks et données de notre page.

Pour ça depuis le HTML5 on aura en plus comme outils les (balises sémantiques)[https://developer.mozilla.org/fr/docs/Glossary/Semantics#les_%C3%A9l%C3%A9ments_s%C3%A9mantiques] qui vont permettre d'utiliser des blocs avec un sens plutôt que des div.

### Les div et span
Ces éléments HTML n'ont presqu'aucun effet et aucune valeur sémantique par eux même. Dès lors, lorsqu'on crée une structure logique, il n'y a pas de raison de les utiliser. Ça ne veut pas dire que leur utilisation est proscrite ou inutile, bien au contraire, il faudra juste réserver leur utilisation pour : faire du CSS (par exemple dans le cas où on veut faire un style css complexe qui nécessite plusieurs éléments html, mais sans pour autant qu'on souhaite modifier notre structure sémantique) ou faire du Javascript (si on veut rajouter des interactions ou autre sans modifier la structure sémantique)

## Créer une structure à partir d'une maquette
![maquette](maquettes/exo-page2.png)

En se basant sur la maquette ci-dessus, l'idée est de créer une [structure HTML](exo-structure.html) pure sans penser au style ou à l'apparence, mais en se concentrant sur ce que représente sémantiquement les différents blocs