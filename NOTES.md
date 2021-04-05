# Mes apprentissages

## HTML

### Important des éléments HTML dans la structure de la page

Il est important d'utiliser des éléments HTML qui ont une signification structurelle pour render la page accessible par des outils autres que le navigateur internet (par exemple, les outils d'énoncé vocale (pour les mal voyants)). L'élément `div` n'a aucune signification sémantique et ne doit être utilisé que pour entourer un élément afin de le décorer (avec du style CSS ou autres...).
Utiliser dès que possible les [éléments sémantique HTML listés ici](https://www.w3schools.com/html/html5_semantic_elements.asp)

- Le main définit le contenu principal de la page: il ne doit pas contenir en enfant directe les éléments `header`/`footer`/`aside` qui sont des éléments adjacents au contenu principal
- La frontière entre `article` et `section` peut-être assez fine. Il faut utiliser l'élément article lorsque son contenu peut vivre en tout autonomie sans être lié à d'autres contenus dans la page: un élément article peut contenir en son sein un header/footer, titre de section (h1...)... L'élement section définit un groupe thématique de contenu avec typiquement un titre de section (définie via `hX`).  Pour plus de détails, voir le forum [Stackoverflow](https://stackoverflow.com/questions/7549561/section-vs-article-html5) ainsi que la charte décisionnelle ci-dessous.
- Différence entre le containeur `header` et les titres de section `hX`: hX (par exemple h1) n'autorise que des éléments textuels et permet de structurer la page en définissant un titre au section. Mais si l'on souhaite utiliser une en-tête plus riche avec des logos, des notes complémentaires (description...), il faut utiliser le container `header`: il est important de noter que l'élément header ne permet pas de délimiter une section dans le document (il n'introduit donc pas de nouvelle section dans la structure). Pour délimiter une section avec l'usage de l'élément `header`, il est nécessaire d'avoir un titre de section avec un élément h1-h6 au sein du header.
- Charte décisionnelle pour choisir le bon élément sémantique:
<img src="https://i.stack.imgur.com/8Ruyj.png" />

### Elément img

- L'attribut `alt` est nécessaire pour décrire une image dans le cas où elle ne peut pas être chargée. Cela permet de donner à l'utilisateur un descriptif textuel de ce que représenterait l'image. Pour plus de détails, voir [ce lien](https://developer.mozilla.org/fr/docs/Web/HTML/Element/Img#attributs) ou encore [celui-ci](https://developer.mozilla.org/fr/docs/Web/HTML/Element/Img#accessibilit%C3%A9).


## CSS

## Liens utiles

- [Validation html](https://validator.w3.org/#validate_by_input)
