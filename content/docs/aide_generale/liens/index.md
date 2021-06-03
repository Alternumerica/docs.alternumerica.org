---
title: "Liens URL"
description: "Qu'est ce qu'un lien URL, principes de base d'internet"
lead: "Qu'est ce qu'un lien URL, principes de base d'internet"
date: 2021-06-02T15:19:44+02:00
lastmod: 2021-06-02T15:19:44+02:00
draft: false
images: []
menu:
  docs:
    parent: "Aide Générale"
weight: 920
toc: true
---

## Lien URL, fondement et ciment d'internet

URL tient pour Uniform Resource Locator ( "localisateur uniforme de ressource" ), on l'appelle également adresse web, et elle sert à identifier une ressource sur internet.
On l'appelle également URI, lien hypertexte ou lien tout court, adresse internet, etc...

Une ressource ? Cela peut-être l'adresse d'un site internet ( https://alternumerica.org ), un lien pour écrire un e-mail ( mailto:info@alternumerica.org ), une [image](https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Historical_image%2C_Skopje.jpg/800px-Historical_image%2C_Skopje.jpg), etc...

C'est au fondement même d'internet, sur internet aujourd'hui chacun est libre de publier une "ressource" ( un texte, une image, un article ) en ligne et d'en communiquer son adresse pour que quiconque puisse y accéder. De la même manière que probablement vous êtes arrivé sur cette page en cliquant sur un lien URL.

C'est le fonctionnement du lien URL qui garanti le fonctionnement décentralisé du web, tel qu'il a été créé par [Tim Berners-Lee](https://fr.wikipedia.org/wiki/Tim_Berners-Lee), chercheur au CNRS, inventeur du World Wide Web.

## Le lien en disparition ?

Lorsque internet a commencé, on ne savait rien faire sans avoir un répertoire d'adresse web. On connaissait l'adresse d'un site internet parce qu'il nous avait été communiqué, on l'avait découvert dans un journal, ou quelqu'un nous en avait parlé. C'était avant l'avènement des moteurs de recherche.
Les moteurs de recherche se sont mis à indexer le web, à en faire un catalogue d'adresse, et ce fut très utile pour pouvoir trouver facilement des informations sur son navigateur.


{{< img src="firefox-google.jpeg" alt="Sur ordinateur" caption="Dans le temps, la barre en haut du navigateur internet était une barre d'adresse, pas une barre de recherche" class="border-0 mx-auto d-block" >}}

Seulement avec le temps, l'URL est devenue de plus en plus transparente, beaucoup pour des problèmes de lisibilité, mais aussi dans une volonté de certains acteurs de s'accaparer des contenus.
Prenons le cas de Facebook par exemple, lorsque vous partager un lien avec une personne sur Facebook, Facebook "digérera" le lien et le rendra inaccessible à son destinataire. Le destinataire recevra le contenu assimilé par Facebook, mais pas le lien qui aura disparu, ceci de manière à inciter de nouvelles personnes à s'inscrire à Facebook pour consulter ces liens.
De plus en plus de navigateur ne montrent plus l'adresse du site que vous visitez.
De plus en plus de boite e-mail ne montrent plus l'adresse complète de la personne qui vous a envoyé un mail.
De plus en plus, on fait disparaître de la vue de l'internaute ce qui fait le fondement même d'internet, le privant ainsi de la capacité de le comprendre.


## Comment se constitue un lien

Prenons le lien de cette page par exemple : </br>
https://alternumerica.org/docs/aide_generale/liens/ </br>

On peut dissocier trois parties dans cette URL :

- **https://** : Correspond au protocole utilisé. Il s'agit ici du protocole HTTP ( HyperText Transfer Protocol ) sécurisé ( addition du "s" ), c'est le protocole utilisé pour toute page ou application web. Le https par rapport au http garanti un chiffrement entre votre ordinateur et le site web, protégeant ainsi des tentatives de piratage sur des réseaux pas toujours bien sécurisé. Cela empêche l'interception de mots de passe par exemple. **Ne saisissez jamais un code de carte bancaire ou un mot de passe important sur une page qui n'est pas en https !**

- **/docs/aide_generale/liens/** : Correspond au chemin sur le site. Tout ce qui se trouve après le nom de domaine correspond ou à des options ou à un chemin particulier indiquant au serveur auquel vous vous adressez quelle ressource en particulier vous désirez obtenir.

- **alternumerica.org** : La partie la plus importante, et celle à laquelle il faut être le plus vigilant. Il s'agit du **nom de domaine**. Un nom de domaine est une sorte d'identifiant renvoyant vers une adresse IP ( de type 0.0.0.0 ) correspondant à l'adresse d'un serveur. Mais ce qui est surtout important à retenir, c'est la structure d'un nom de domaine, et de **bien faire la différence entre un nom de domaine et un sous-domaine** !
Le nom de domaine est toujours en deux parties séparées par un **"."** : alternumerica.org est un nom de domaine, cloud.alternumerica.org ( l'adresse du Cloud de Alternumerica ) est un sous-domaine.
Lorsque vous louez un nom de domaine ( peut se louer chez de nombreux fournisseurs, alternumerica.org est loué chez OVH ), vous devenez possesseurs de tous les sous-domaines que vous souhaitez créer.
**En louant le domaine alternumerica.org, Alternumerica peut créer n'importe quel sous-domaine finissant par alternumerica.org.**

C'est important à comprendre quand vous voulez éviter de vous faire avoir par une arnaque sur internet, voilà un exemple de cas où il est important de comprendre :
- google.alternumerica.org est un site appartenant à Alternumerica.
- alternumerica.google.com est un site appartenant à Google.

C'est très important à prendre en compte ! Si un jour vous recevez un mail de votre banque qui vous renvoie par exemple vers une adresse ressemblant à https://banquepostale.liuo.com, ne faites surtout pas confiance, parce que cette adresse est un sous-domaine de liuo.com et n'appartient donc pas à banquepostale.com !

Comprendre les grandes lignes de comment se compose une adresse URL est important pour saisir un petit peu ce qui se passe quand vous cliquez sur un lien.
