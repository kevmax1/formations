- Introduction
    - Qu'est ce que le CSS ?
    - Qu'est ce que l'on va voir dans cette formation ?
    - Quel éditeur utiliser ? (bracket peut être ?)
    
## Le langage

- Comment écris-t-on du CSS ?
    - L'attribute style 
    - la balise `<style>`  
    - Dans un css séparé via `link` 
    - La syntaxe : selecteur { propriété: valeur }` 
    - les status (:hover, :focus...)
    - les unités (calculé, spécifié, [W3C unitit](https://www.w3.org/Style/Examples/007/units.fr.html) et les untiés de couleur rgba
- La notion de priorité (quelle règle l'emporte) aka https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity [specificity CSS](https://specificity.keegan.st/)
 Préciser la notion d'héritage en CSS (Author / User / UA...) dans le point précédent
- Prefix navigateur et notion de compatibilité (découverte de caniuse.com et autoprefixer)

## Les règles

On ne peut pas présenter toutes les règles mais le but est de donner une base de départ et de présenter quelques règles incontournables et surtout la bible : https://developer.mozilla.org/fr/docs/Web/CSS/Reference

-Layout
    - Box-model
    - Display
        - inline vs block
        - inline-block
        - table
        - flex (à placer dans un chapitre pour plus tard)
    - Dimensions
        - margin / padding, comment on peut mettre une valeur négative ? dafuk ?
        - La fusion des marges
        - width, height, min-width, max-height...[width et min-width](http://goetter.tumblr.com/post/64119638003/quiz-parce-que-la-taille-%C3%A7a-compte)
    - Position
        - static
        - absolute (et donc voir le relative) top left right bottom
        - fixed / sticky
    - Containing block
    - Float (ça mérite un chapitre entier XD)
    - Block Formatting Context
    - z-index et le context d'empilement [contexte d'empilement](http://iamvdo.me/blog/comprendre-z-index-et-les-contextes-dempilement)
    
    Sinon toutes les surprises de CSS [merci iamvdo](http://iamvdo.me/blog/ce-que-vous-avez-toujours-voulu-savoir-sur-css)
    
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
- Transform
    - translate
    - rotate
    - scale
    
## Travaux pratique 

- Intégration de la maquette : https://dribbble.com/shots/1567242-FREE-PSD-Multipurpose-Landing-Page/attachments/319370 

## Notions avancées

- Media query
- Transitions
- Animations
- les grilles [via raphael goetter](https://blog.goetter.fr/2014/10/27/le-point-sur-les-grilles-en-css/)
- framework CSS

## "Bonnes Pratiques" <= renommer ça parceque ça fait genre j'impose la manière de faire les choses :)

- Mobile First
- SMACSS / BEM / OOCSS
- Les preprocesseurs: sass, less, stylus, postCSS

## le futur 
- CSS4 selecteur
- filter()
- variable css
- shape
- césure
- [cssnext](http://cssnext.io/)
