# SMALA, en mode Agile

![Logo de l'appli web SMALA](smala-logo-v02-web-comp.svg)

Vous vous rappelez de Georges, cet ami développeur qui avait travaillé avec vous sur le projet "faceBoom" ? Et bien Georges est de retour, avec de nouvelles inspirations. Georges laisse tomber le nom "faceBoom", un peu trop militant et opte pour la "SMALA".

SMALA est une appli web qui va permettre à celles et ceux qui le souhaitent d'héberger leurs photos personnelles sur les serveurs de leur choix, gratuitement, sans publicité et sans aucun pisteur (tracker), pour la plus grande joie des données personnelles.

## Modalités pédagogiques

- Projet à effectuer en deux semaines
- Travail en groupe prédéfini par l'équipe pédagogique
- Travail organisé selon la méthode [Kanban](https://fr.wikipedia.org/wiki/Kanban_(d%C3%A9veloppement)) ou [Scrum](https://fr.wikipedia.org/wiki/Scrum_(d%C3%A9veloppement))
- Projet à rendre individuellement
- Compétences C1-C7 (sauf C4) du [RÉAC](https://cdn.hmz.tf/REAC_DWWM_V03_03052018.pdf)

## Agilité

- Le groupe définit un [product owner](https://en.wikipedia.org/wiki/Scrum_(software_development)#Product_owner) [mais qui fait parti de l'équipe de dev<sup>1</sup>]
- Le groupe définit un [scrum master](https://en.wikipedia.org/wiki/Scrum_(software_development)#Scrum_master) [mais qui fait parti de l'équipe de dev<sup>1</sup>]

<sup>1</sup> Normalement ce n'est pas le cas. Le product owner ou le scrum master ne font pas parti de l'équipe de dev. Mais pour des raisons de temps et d'organisations, exceptionnellement, ils codent également !

## Votre mission

Créer une application web sur-mesure, en vous basant sur les user stories fournies par le client.

## User stories

Les robots des moteurs de recherche ne peuvent pas indexer les photos publiées dans une SMALA. Raison pour laquelle il existe trois rôles dans une SMALA :

- rôle visiteur : aucun accès, à part la page de connexion
- rôle utilisateur :
  - peut voir toutes les photos
  - peut ajouter de nouvelles photos
  - peut supprimer les photos **qu'il a lui-même ajoutées**
  - peut éditer son profil (pseudo, email, mot de passe)
- rôle administrateur :
  - peut voir toutes les photos
  - peut ajouter de nouvelles photos
  - peut supprimer les photos **de n'importe quel utilisateur ou administrateur**
  - peut éditer son profil (pseudo, email, mot de passe, **rôle**)
  - peut ajouter un autre utilisateur
  - peut éditer le profil d'un autre utilisateur (pseudo, email, mot de passe, rôle)

## Critères de performance

- Le projet doit être organisé selon la méthode [Kanban](https://fr.wikipedia.org/wiki/Kanban_(d%C3%A9veloppement)) ou [Scrum](https://fr.wikipedia.org/wiki/Scrum_(d%C3%A9veloppement))
- Le nommage des variables doit être clair et cohérent
- Faire attention à l'indentation de votre code
- Le site doit être avant tout conçu pour une utilisation sur mobile (mobile first)
- Vous avez carte blanche pour le rendu visuel (framework css autorisé)
- Vous avez carte blanche sur la techno back-end (utilisation d'un framework possible)

## Ressources
- https://blog-gestion-de-projet.com/comment-organiser-son-product-backlog/
- https://blog.adimeo.com/scrum-master
- https://fr.wikipedia.org/wiki/Scrum_(d%C3%A9veloppement)#Glossaire
- https://fr.wikipedia.org/wiki/Scrum_(d%C3%A9veloppement)#Caract%C3%A9ristiques_essentielles
- https://www.beekast.com/fr/blog/10-exemples-de-retrospectives-agiles-a-animer-avec-beekast/
- https://trello.com/
- https://cryptpad.roflcopter.fr/kanban/

## Livrables

- Lien vers le backlog 
- Lien vers les users stories
- Lien vers le détail des sprints hebdomadaires
- Lien vers le dépot Git contenant le projet web
- Lien vers une démo en ligne (accompagné d'un identifiant et mot de passe valides)
- Lien vers la rétrospective agile (qui sera utilisée lors de la présentation devant le groupe)

## Contexte du projet

Parfois la création d'une application web peut être demandée par un client. Un développeur se doit d'être capable de produire ce type de site et de travailler en équipe, grâce aux pratiques agiles, tout en respectant les étapes de production.

## Du son pour coder
- [Moonwater, de Himemaki](https://www.youtube.com/watch?v=OtXfBaQ0_sw)
- [Tous les matins du monde, de Jordi Savall](https://www.youtube.com/watch?v=uORg1aeD_Og&list=OLAK5uy_n9w1o7KMRtXECTGuBcAszJ9G1mu1uzfRc)

## Pour aller plus loin

Vous avez terminé le brief ? Alors voici de quoi aller plus loin.

### Déploiement d'une SMALA
Lorsque l'on installe une nouvelle SMALA sur un server, un petit "setup" nous permet de créer le premier compte utilisateur. Ce premier compte sera un compte administrateur.