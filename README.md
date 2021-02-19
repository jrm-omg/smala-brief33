# SMALA, en mode Agile

![Logo de l'appli web SMALA](smala-logo-v02-web-comp.svg)

Vous vous rappelez de Georges, cet ami développeur qui avait travaillé avec vous sur le projet "faceBoom" ? Et bien Georges est de retour, avec de nouvelles inspirations. Georges laisse tomber le nom "faceBoom", un peu trop militant et opte pour la "SMALA".

SMALA permet à celles & ceux qui le souhaitent d'héberger leurs photos personnelles sur les serveurs de leur choix. Gratuitement. Sans publicité. Sans pisteur (tracker). Et dans le plus strict respect des données personnelles.

Techniquement, on déploie une SMALA sur un server, tout comme on y déploierait "un Wordpress".

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

Créer une application web sur mesure, en vous basant sur les scénarii utilisateurs fournis par le client.

## Scenarii utilisateur

On dit **un** scénario et **des** scenarii, n'est-ce pas ? Et bien en voici quelques-un, classés par rôle.

### Administrateur
- Une fois déployé sur un serveur (fichiers & base de données), SMALA propose de créer le premier des comptes utilisateurs : celui dont le rôle sera "admin". Un compte utilisateur est composé d'un pseudo, d'une adresse mail, d'un mot de passe ainsi que d'un rôle (rôle utilisateur ou rôle admin).
- Lorsque le premier compte utilisateur (admin) est créé, SMALA lui propose de se connecter à l'interface d'administration du site.
- L'interface d'administration pour l'utilisateur dont le rôle est admin (on l'appellera "l'administrateur") permet de gérer les autres comptes utilisateurs (CRUD).
- L'administrateur peut gérer toutes les photos présentes et les supprimer s'il le souhaite.
- En plus de ses superpouvoirs, l'administrateur peut effectuer les mêmes opérations qu'un utilisateur (voir en dessous)

### Utilisateur
- Un utilisateur doit s'être identifié (via son adresse email et son mot de passe) pour pouvoir accéder à la SMALA.
- Un utilisateur accède à **toutes les photos** postées par **tous les utilisateurs** de cette SMALA
- Les photos sont classées par ordre chronologique, de la plus récente à la plus ancienne.
- Le "[call to action](https://en.wikipedia.org/wiki/Call_to_action_(marketing))" de l'utilisateur est un bouton qui l'invite à poster une nouvelle photo.
- Un utilisateur peut gérer uniquement ses photos et les supprimer.
- Un utilisateur peut accéder à son profil et en modifier son pseudo, son adresse email et un nouveau mot de passe.
- Un utilisateur ne peut pas changer son rôle (et devenir ainsi admin, vilain).
- Un utilisateur n'accède pas à la gestion des autres comptes utilisateurs, contrairement à l'administrateur.

### Visiteur
- Un visiteur n'a pas accès au contenu d'un site SMALA, il doit obligatoirement s'identifier en tant qu'utilisateur, ce qui permet de protéger la SMALA et son contenu des robots pilotés par les moteurs de recherche.

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