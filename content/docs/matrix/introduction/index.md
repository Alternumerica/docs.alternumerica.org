---
title: "Introduction à Matrix"
description: ""
lead: ""
date: 2021-05-30T07:52:59+02:00
lastmod: 2021-05-30T07:52:59+02:00
draft: false
images: []
menu:
  docs:
    parent: "matrix"
weight: 210
toc: true
---



Matrix est un protocole de messagerie instantanée plus connu par sa principale application Element.
Matrix a été crée en 2015 et a été concu de l'idée de créer un système de messagerie instantanée **décentralisée** et **fédérée**, reposant sur un code source **libre** et **ouvert**.

### Décentralisée et fédérée ?

Le principe fondamental de Matrix est que plusieurs serveurs peuvent fonctionner ensembles et communiquer entre eux. Qu'est ce que ça veut dire ? Et bien que comme le mail, quelqu'un possédant une adresse email chez gmail ( exemple@gmail.com ) peut communiquer avec quelqu'un possédant une adresse prontonmail ( exemple@protonmail.com ) bien que les données soient conservées sur des serveurs différents n'appartenant pas aux mêmes acteurs.

### L'intéret ?

La libre concurrence.
La prévention de monopoles.
La liberté de choix.

En Janvier 2021, WhatsApp a annoncé à tous ses utilisateurs un changement de politique concernant les données personnelles. Pas un gros changement certes, ils annonçaient que les données récupérées par WhatsApp seraient désormais partagées avec Facebook ( comme WhatsApp a été racheté par Facebook en 2014, il est difficile de croire que cet échange n'existait pas avant ). Donc toutes les données, heure des appels, les personnes avec qui ses utilisateurs sont en contact, les groupes auxquels ses utilisateurs participent, etc... Pouvaient dorénavant être utilisés à des fins publicitaires.

Pas d'accord ? Allez vous faire voir. Vous pouvez quitter WhatsApp et abandonner tous vos contacts.
Beaucoup de gens ont quitté WhatsApp pour Signal à ce moment, seulement Signal repose sur une architecture isolée comme WhatsApp et est [irrémédiablement voué à conduire au même problème](https://matrix.org/blog/2020/01/02/on-privacy-versus-freedom).

L'idée de Matrix est de créer une architecture pouvant éviter cela. Vous possédez un compte chez matrix.org ( @exemple:matrix.org ) et vous n'êtes plus satisfaits de leur politique ? Vous pouvez migrer votre compte chez converser.eu ou tchns.de par exemple et continuer à communiquer avec vos contacts en confiant vos données à quelqu'un d'autre.
Cela évite surtout qu'un seul et unique prestataire puisse avoir accès aux données du monde entier.

### Libre et ouvert ?

Tout le code source ( la recette ) des logiciels faisant tourner l'écosystème Matrix sont [disponibles en ligne](https://github.com/matrix-org/).

Leur fonctionnement est donc totalement transparent. Et tout un chacun peut récupérer le code gratuitement pour créer son propre serveur Matrix.


### Si vous ne payez pas c'est que vous êtes le produit ?

Ou posée différemment, comment se finance Matrix ?
Matrix est une fondation soutenue par une compagnie privée, Element ( à l'époque Vector.im ), basée en angleterre et fondée par un anglais, Matthew Hogdson et une française, Amandine Le Pape.
La fondation Matrix est soutenue par différents donateurs, comme Mozilla, Automattic ( la société derrière Wordpress, moteur de site web ) et divers acteurs européens.
La société Element se finance par un service payant, plus complet que ceux fournit par matrix.org, disponible sur https://element.io/pricing, principalement destiné à un usage professionel.
La société Element joue aussi le rôle de consultant pour des organismes souhaitant installer leurs propres serveurs. Les cas les plus notables sont l'administration Française qui a fait appel à Element pour monter son propre serveur Matrix pour l'application [Tchap](https://www.tchap.gouv.fr/), ou l'armée allemande qui a choisi [Matrix pour ses communications internes](https://techastuce.com/matrix-instant-messenger-la-bundeswehr-mise-sur-lopen-source-en-service/).
Matrix est aussi installé dans de [nombreuses universités en Allemagne](https://doc.matrix.tu-dresden.de/en/why/) et commence à être utilisé dans certains hopitaux avec un système de chat en ligne direct.

### Les applications ?

Si Matrix est le protocole de communication, les applications pour l'utiliser sont nombreuses à se développer.
La principale et la plus connue est Element, anciennement connue comme Riot.
Mais il existe d'autres application. Fluffychat est une application reposant sur Matrix également.

Mozilla prévoit d'intégrer un chat Matrix dans son application email Thunderbird. Il existe sinon Nheko, Fractal, Neochat, etc...
[La liste se trouve ici](https://matrix.org/clients/).

Toutes ces applications sont intercompatibles, et sont le choix de l'utilisateur. Vous avez déjà un compte Matrix mais vous n'aimez pas vraiment l'interface de Element ? Vous pouvez simplement vous connectez avec votre même compte Matrix sur une application différente et retrouver toutes vos discussions sur une interface différente.


### Matrix sur Alternumerica

En utilisant un compte Matrix avec Alternumerica, vous bénéficiez d'un service plus rapide ( car moins encombré ) qu'avec le serveur matrix.org, vous bénéficiez de l'accès à des salons d'aide et êtes en contact direct avec des développeurs et utilisateurs avancés qui essaieront de vous assister dans vos problèmes d'informatique.
Vous bénéficiez aussi de l'accès à des bots spécifiques, vous permettant par exemple de recevoir et d'envoyer vos messages WhatsApp, Messenger, Telegram sur votre messagerie Element.
