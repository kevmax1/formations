- Introduction
    - Qu'est ce que le CSS ?
    - Qu'est ce que l'on va voir dans cette formation ?
    - Quel éditeur utiliser ? (bracket peut être ?)
    
## Le langage

- Comment écris-t-on du CSS ?
    - L'attribute style 
    - la balise `<style>`  
    - Dans un css séparé via `link` 
    - La syntaxe : `selecteurs { propriété: valeur }` 
    - Les combinators (`>`, `+`, `~`, ...)
    - Les pseudo-classes (`:hover`, `:focus`, ...)
    - Les pseudo-elements (`::after`, `::before`, ...)
- La notion de priorité (quelle règle l'emporte, !important) aka https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity. Préciser la notion d'héritage en CSS (Author / User / UA...)
- Prefix navigateur et notion de compatibilité (découverte de caniuse.com et autoprefixer)

## Les règles

On ne peut pas présenter toutes les règles mais le but est de donner une base de départ et de présenter quelques règles incontournables et surtout la bible : https://developer.mozilla.org/fr/docs/Web/CSS/Reference

- La police
    - font-family
    - font-weight
    - line-height
    - color
    - text-transform
    - font-style
    - letter-spacing
    - text-shadow
    - text-align
    - @font-face, https://developer.mozilla.org/fr/docs/Web/CSS/@font-face
- Apparence
    - background
    - border
    - box-shadow
- Display
    - inline vs block
    - inline-block
    - table
    - flexbox (à placer dans un chapitre pour plus tard)
- Box-model
    - margin / padding, comment on peut mettre une valeur négative ? dafuk ?
    - La fusion des marges
    - width, height, min-width, max-height...[width et min-width]
    - box-sizing (oh le padding agrandit nos largeurs !)
    (http://goetter.tumblr.com/post/64119638003/quiz-parce-que-la-taille-%C3%A7a-compte)
    - containing block (https://www.w3.org/TR/CSS21/visudet.html#containing-block-details)
    - Block Formatting Context (http://www.alsacreations.com/astuce/lire/1543-le-contexte-de-formatage-block-en-css.html)
- Position
    - static
    - absolute (et donc voir le relative) top left right bottom
    - fixed / sticky
    - z-index et le context d'empilement [contexte d'empilement](http://iamvdo.me/blog/comprendre-z-index-et-les-contextes-dempilement)
- Float (ça mérite un chapitre entier XD)
- Transform
    - translate
    - rotate
    - scale
    
## Travaux pratique 

- Intégration de la maquette : https://dribbble.com/shots/1567242-FREE-PSD-Multipurpose-Landing-Page/attachments/319370 

## Notions avancées

- Les unités : %, px, em, rem, ch, vw / vh - vmin / vmax
- Media query
- Transitions
- Animations
- Flexbox

## Conseils pratiques et outils

- Grille
- Framework CSS
- Sprite et Font icones
- Mobile First
- SMACSS / BEM / OOCSS
- Les preprocesseurs: sass, less, stylus, postCSS, nextCSS

## le futur 

- CSS4 selecteur
- filter()
- Variable css
