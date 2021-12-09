# NewsWeb
Création d'un site de type "Journal" contenant des news à propos du Web.

Les consignes sont dans le fichier  : newsweb_v1.pdf

Le template d'origine a été téléchargé sur le site Free-CSS.com et décompressé dans le dossier /sources
https://www.free-css.com/free-css-templates/page183/sourcexsrt

A partir du design d'origine, on établit 3 mises en page pour des tailles d'écran différentes
1. pour smartphone (écran de largeur <= 599px>)
2. pour tablette (écran de largeur entre 600px et 1024px)
3. pour PC Desktop (écran de largeur > 1024px)

Un aperçu des mises en page peut être vu sur le fichier : DesignSite.png

## Desktop

On part du fichier index.html d'origine et on le renomme index.html.original
On fait une copie et on la renomme index_desktop.html

- on enlève la zone "Latest Projects" avant le footer
- on modifie le texte du logo
- on modifie les éléments du menu
- on modifie dans la zone des articles, le titre principal, les titres des articles, les boutons "Read more"
- on modifie le footer
- on complète l'entête de page <head>

On passe ensuite à la CSS

- on modifie la largeur du wrapper global
- on supprime la texture du fond et on remplace par une couleur de fond
- on modifie le logo pour rapprocher les textes
- on adapte le slider
- on centre le titre "Nos derniers articles"
- on adapte les boutons "En savoir plus..."
- on adapte les articles en les répartissant sur toute la largeur
- on centre le footer

## Tablette

On réalise la mise en page avec CSS Grid
- le logo reste au-dessus
- le menu devient vertical à gauche
- les articles sont placés à droite du menu
- le 1er article (le plus récent) occupe toute la largeur restante à côté du menu
- les 2è et 3è articles les plus récents se répartissent 50/50 la largeur sous le 1er article
- le footer est tout en bas

NB: on décide de ne plus afficher le slider

## Smartphone

On réalise la mise en page avec CSS Flexbox
- Le logo et un menu hamburger au-dessus
- les 3 articles en-dessous
- le footer tout en bas

NB: on décide de ne plus afficher le slider