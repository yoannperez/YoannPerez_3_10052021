![](public/Images/ohmyfood.png)
***
# Création du site Ohmyfood! Paris
***

### Equipe:
* Paul, CTO.
* Fanny, UX designer.
* Anissa, commerciale.
* Yoann, développeur web.

## Contraintes techniques
###Technologies:
* Le développement devra se faire en CSS, sans JavaScript. =>VERIFIE
* Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus. =>VERIFIE
* Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.
=>VERIFIE

### Charte graphique:
* Primaire #9356DC
* Secondaire: #FF79DA
* Tertiaire: #99E2D0

Seules des maquettes mobiles sont réalisées. Pour faire rapide, quelques modifications légères ont été fait au code pour supporter les version tablettes et mobiles, ce qui réduira le coût de maintenance pour les évolutions futures du site.

### 	Breakpoints:
* mobile: 576px,
* tablets: 992px,
* computer: 1200px.


* Code: HTML & CSS ( mise en forme : FlexBox )
* IDE: VS Codium
* W3C validator : To check
* Compatibilité: Vérifié sur Chrome & Firefox

## Contenu des pages:
### Page d’accueil (x1)
* Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
* Une courte présentation de l’entreprise.
* Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.

## Pages de menu (x4)
* 4 pages contenant chacune le menu d’un restaurant.

## Footer
* Le footer est identique sur toutes les pages.
* Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

## Header
* Le header est présent sur toutes les pages.
* Sur la page d’accueil, il contient le logo du site.
* Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

### Effets graphiques et animations - Checklist
Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.

### Boutons
* Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
* À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.
* Page d’accueil
* Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, c
* ouvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.
* Pages de menu
* À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
* Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.

Améliorations apportées en sus des impératifs du projet :
- Adaptation mobile.
- temps de chargement des fontes

