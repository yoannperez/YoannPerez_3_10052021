![](public/Images/ohmyfood.png)
***
# Création du site Ohmyfood! Paris

Vous trouverez ici les fichiers rendus pour le projet 03 "Ohmyfood" réalisé dans le cadre du parcours développeur web proposée sur la plateforme Openclassrooms [https://openclassrooms.com/fr/paths/185-developpeur-web](https://openclassrooms.com/fr/paths/185-developpeur-web).

Le site est en ligne à l'adresse suivante :
[https://yoannperez.github.io/YoannPerez_3_10052021/index.html](https://yoannperez.github.io/YoannPerez_3_10052021/index.html)

***
##Comment utiliser ce dépot ?

Pour rapatrier ce projet en local, utiliser la commande :

```
$ git clone git@github.com:yoannperez/YoannPerez_3_10052021.git
```
Déplacez-vous dans le dossier :


```
$ cd YoannPerez_3_10052021
```

Dans le cas où vous voulez vous référer aux fichiers sass plutôt que le code css directement, il vous faudra [sass](https://sass-lang.com/) installé sur votre machine. 

Télécharger et installer le logiciel NodeJS à cette adresse :
[https://nodejs.org/en/download/](https://nodejs.org/en/download/)

Pour installer les dépendances du projet :

```
$ npm install
```



Puis enfin :

```
$ npm run sass
```
 
dans votre dossier local pour compiler les fichiers sass en un fichier /public/CSS/styles.css référencé dans les fichiers html.


***
### Composition de l'équipe:
* Paul, CTO.
* Fanny, UX designer.
* Anissa, commerciale.
* Yoann, développeur web.

## Contraintes techniques
###Technologies:
* Le projet est développé en CSS, sans JavaScript ( mise en forme : FlexBox ).
* Aucun framework n'est utilisé, en revanche le projet est écrit et organisé à l'aide de SASS. 
* Aucun code CSS n'est appliqué via un attribut style dans une balise HTML.

### Charte graphique:
* Primaire #9356DC
* Secondaire: #FF79DA
* Tertiaire: #99E2D0

Seules des maquettes mobiles ont été réalisées. Quelques modifications légères ont été apportées au code pour supporter les version tablettes et desktop.

### 	Breakpoints:
* mobile: 576px,
* tablets: 992px,
* computer: 1200px.

Les médias queries sont réalisées à l'aide de mixins contenues dans le fichier /sass/utils/_queries.scss. Une modification des breakpoints est posible en modifiant les données de la map $breakpoints.

### 	Autres informations techniques:
* IDE utilisé: VS Codium
* W3C validator : Checked
* Compatibilité: Vérifié sur Chrome, Firefox, Edge & Safari

## Contenu des pages:
### Page d’accueil (x1)
* Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
* Une courte présentation de l’entreprise.
* Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.
* Une seconde version de la page d'acceuil a été réalisée afin de faciliter la navigation lors de l'exploration de la maquette.
### Pages de menu (x4)
* 4 pages contenant chacune le menu d’un restaurant.

### Footer
* Le footer est identique sur toutes les pages.
* Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

### Header
* Le header est présent sur toutes les pages.
* Sur la page d’accueil, il contient le logo du site.
* Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

## Effets graphiques et animations - Checklist
Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils utilisent les animations ou transitions CSS, pas de JavaScript ni de librairie.

### Boutons
* Au survol, la couleur de fond des boutons principaux s’éclaircissent légèrement. L’ombre portée est également plus visible.


* À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il se remplit progressivement. Pour cette première version, l’effet apparaît au survol sur desktop au lieu du clic.

### Page d’accueil
Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous en avons un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). 

Le design de ce loader n’est pas défini.

### Pages de menu


* À l’arrivée sur la page, les plats apparaissent progressivement avec un léger décalage dans le temps.


* Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche coulisse de la droite vers la gauche. Pour cette première version, l’effet apparaît au survol sur desktop au lieu du clic. 

* Si l’intitulé du plat est trop long, il est rogné avec des points de suspension.
