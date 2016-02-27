# mobile kaye

> Side notes for the mobile part of the webdesign course of HEPL.

* * *

**Note:** the school where the course is given, the [HEPL](http://www.provincedeliege.be/hauteecole) from Liège, Belgium, is a french-speaking school. From this point, the instruction will be in french. Sorry.

* * *

Dans le cadre de nos cours de labo, il nous arrivera souvent de digresser et d'aborder certains sujets qui, s'ils sortent du cadre du cours de *Design web mobile*, n'en restent pas moins intéressants pour votre formation et/ou votre culture de futur infographiste/développeur web.

Le présent document référencera ces discussions et les éventuels liens qui s'y rapportent.

## Préprocesseurs CSS

* [LESS](http://lesscss.org/)
* [Sass](http://sass-lang.com/)
  * [Compass](http://compass-style.org/), framework pour Sass
  * [Bourbon](http://bourbon.io/), framework pour Sass
    * [Neat](http://neat.bourbon.io/), système de grille pour Sass/Bourbon
    * [Bitters](http://bitters.bourbon.io/), styles de base pour Sass/Bourbon
    * [Refills](http://refills.bourbon.io/), composants pour Sass/Bourbon
* [Stylus](http://stylus-lang.com/)
  * [Kouto Swiss](http://kouto-swiss.io/), framework pour Stylus

### Compilateurs graphiques

* [Prepros](https://prepros.io/), gratuit (avec pub), multi-plateformes
* [Codekit](https://incident57.com/codekit/), payant (32$), Mac OS uniquement

## ITCSS

* [Présentation des concepts de ITCSS](https://speakerdeck.com/dafed/managing-css-projects-with-itcss) (slides).

### Tableau récapitulatif de ITCSS

| Niveau | Nom de la couche | Fonction |
| :----: | :--------------- | :------- |
| 1 | Settings | Variables globales |
| 2 | Tools | Mixins globaux, functions & outils |
| 3 | Generic | Style de remise à zéro (reset, normalize…) |
| 4 | Base | Éléments bruts |
| 5 | Objects | Éléments de mise en forme non-cosmétique | 
| 6 | Components | Design des composants, morceaux d'UI |
| 7 | Trumps | Styles spécifiques à un élément |

* * *

## Design Mobile

### Guidelines 

* [Guidelines iOS](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/)
* [Guidelines Android](http://developer.android.com/design/index.html)

### Wireframing

* [sneakpeek it](http://sneakpeekit.com/), une série de feuilles vierge à télécharger puis imprimer pour faire des wireframes.
* [UI stencils](http://www.uistencils.com/), boutique d'accessoires pour le wireframing.
* [The 20 best wireframe tools](http://www.creativebloq.com/wireframes/top-wireframing-tools-11121302), une liste (récente) d'apps pour faire des wireframes.
* [BLOKK](http://blokkfont.com/), une police pour simuler de longs blocs de texte.

* * *

## Divers

### dotfiles

Pour ceux qui s'intéressent à la problématique des `.dotfiles`, l'un des articles fondateurs à ce sujet est le suivant : [Getting started with dotfiles](https://medium.com/@webprolific/getting-started-with-dotfiles-43c3602fd789).  
Le colossal repository [awesome-dotfiles](https://github.com/webpro/awesome-dotfiles) regroupe toute une série de liens vers des outils, articles et références sur le sujet, ainsi qu'une liste de repos d'utilisateurs confirmés, pour inspiration.  
Enfin, pour info, mes dotfiles sur trouvent sur le repo [leny/pwendok](https://github.com/leny/pwendok).
