---
title: "Mots de passe"
description: "Conseils sur la gestion de vos mots de passe"
lead: ""
date: 2021-06-01T15:13:04+02:00
lastmod: 2021-06-01T15:13:04+02:00
draft: false
images: []
menu:
  docs:
    parent: "Aide Générale"
weight: 930
toc: true
---

## Introduction aux différentes méthodes de gestion de mots de passe.

Il existe de nombreuses solutions pour gérer vos mots de passe en ligne, nous allons passer en revue les différentes méthodes de la **pire aux meilleures** et essayer de voir avantages et inconvénients :

- Mettre le même mot de passe pour tous les sites : **La pire méthode**.

  Rien de pire au niveau sécurité. Il suffit que la sécurité de votre mot de passe soit compromis, ou pire de carrément tomber sur un site internet sans scrupule qui récupère votre mot de passe et votre nom d'utilisateur pour les transmettre à des gens mal intentionnés pour que ces personnes s'ouvrent un accès sur tous vos différents comptes en ligne.

  **Oubliez cette méthode !!**

- Enregistrez vos mots de passe dans un fichier texte : **Dangereux**.

  Enregistrer vos mots de passe dans un fichier est une solution simple pour les retenir et ne pas les perdre. L'avantage est que vous pouvez garder une copie de vos mots de passe et les recopier facilement pour ne pas les perdre. Mais un fichier a vite fait de se retrouver dans la nature, un piratage, une erreur malencontreuse, et tous vos mots de passe se retrouvent dans la nature.

- Enregistrer vos mots de passe dans un navigateur : **Pas une si mauvaise solution**.

  Enregistrer vos mots de passe dans un navigateur n'est pas une si mauvaise solution. D'abord ils sont remplis automatiquement lorsque vous naviguez sur les sites, et vous pouvez les retrouver facilement en naviguant dans le menu de votre navigateur internet.
  Le principal inconvénient est que les mots de passe restent accessibles en clair à quelqu'un qui utiliserait votre ordinateur, ou le volerait. Et tous les mots de passe ne sont pas des mots de passe de sites internet.

- Utiliser un gestionnaire de mots de passe : **La meilleure des solutions**.

  Utiliser un gestionnaire de mots de passe est de loin la meilleure des solutions pour conserver vos mots de passe en toute sécurité. Ils permettent de conserver vos mots de passe en les protégeant par un mot de passe général.
  Un gestionnaire de mots de passe est disponible sur le [Cloud d'Alternumerica](https://cloud.alternumerica.org), mais le meilleur et le plus complet des gestionnaires de mots de passe reste **Keepass**.


## Présentation de Keepass

Il existe différentes version de Keepass, Keepass étant un **logiciel libre**, différentes personnes et organismes en ont créé différentes versions.
Nous allons nous concentrer ici sur KeepassXC, disponible au téléchargement sur https://keepassxc.org/

KeepassXC vous permet de **conserver vos mots de passe**, **conserver des fichiers secrets**, configurer des authentifications doubles avec **TOTP**, etc...

**Téléchargez KeepassXC et installez le** sur votre ordinateur.

{{< img src="keepass-intro.jpeg" alt="Sur ordinateur" class="border-0 mx-auto d-block" >}}

Considérant que cela est votre **première utilisation** de Keepass, cliquez sur **Créer une nouvelle base de données**.

{{< img src="creer-une-base-de-donnees.jpeg" alt="Sur ordinateur" class="border-0 mx-auto d-block" >}}

Vous pouvez alors choisir un nom et une description pour la base de données.
Cliquez ensuite sur **Continuer**.

{{< img src="parametres-de-chiffrement.jpeg" alt="Sur ordinateur" class="border-0 mx-auto d-block" >}}

Sur l'écran de paramètres de chiffrement, il n'y a rien à changer, à moins que vous ne sachiez ce que vous faites. Cliquez sur **Continuer**.

{{< img src="identifiants-keepass.jpeg" alt="Sur ordinateur" class="border-0 mx-auto d-block" >}}

Vous pouvez maintenant choisir votre **mot de passe central**, vous n'aurez que ce mot de passe à retenir, mais **ne l'oubliez pas !!!**, en cas de **perte** du mot de passe, il sera **impossible** de déchiffrer à nouveau cette base de donnée. Il serait peut-être prudent de noter ce mot de passe dans un lieu sûr au cas où dans un premier temps.

Vous pouvez également **ajouter une protection supplémentaire**.

Et cliquer sur **Ajouter un fichier clé**.

{{< img src="ajout-fichier-cle.jpeg" alt="Sur ordinateur" class="border-0 mx-auto d-block" >}}
{{< img src="generer-fichier-cle.jpeg" alt="Sur ordinateur" class="border-0 mx-auto d-block" >}}

Cliquez sur **Générer**.

Vous arriverez sur un écran de sauvegarde :
{{< img src="key-name.jpeg" alt="Sur ordinateur" class="border-0 mx-auto d-block" >}}

N'oubliez pas de **choisir un nom** pour votre fichier clé, et choisissez le dossier dans lequel vous souhaitez le conserver.

*Notre Recommandation: Stockez votre clé dans un dossier confidentiel, ou dans une clé USB dont vous ferez une copie. Vous pourrez facilement faire des copies du fichier générer et le conserver sur plusieurs clés USB. Ainsi vous ne pourrez accéder à vos mots de passe qu'avec votre clé USB insérée dans votre ordinateur. **N'oubiez pas : sans ce fichier clé vous ne pourrez plus ouvrir vos mots de passe***

Cliquez bien ensuite sur **Sauvegarder**.

{{< img src="keepass-terminer.jpeg" alt="Sur ordinateur" class="border-0 mx-auto d-block" >}}

Une fois votre mot de passe saisi, et votre fichier clé configuré, vous pouvez maintenant cliquer sur **Terminer**.

{{< img src="save-base-de-donnee.jpeg" alt="Sur ordinateur" class="border-0 mx-auto d-block" >}}

choisissez maintenant l'emplacement de la sauvegarde de votre fichier de base de données, le mieux est de le conserver dans un dossier qui est sauvegardé/synchronisé. Une bonne solution est de le mettre dans votre dossier synchronisé avec le Cloud d'Alternumerica !

{{< img src="keepass-done.jpeg" alt="Sur ordinateur" class="border-0 mx-auto d-block" >}}

Vous voilà maintenant avec une nouvelle base de donnée keepass. Vous pouvez commencer à entrer vos mots de passe.

Récapitulons, vous aurez à présent besoin de 3 éléments pour ouvrir votre base de donnée :
- la **base de donnée** elle-même, elle contient tous vos mots de passe et sera changeante, synchronisez la avec votre Cloud, même si quelqu'un venait à récupérer votre base de donnée, il ne pourrait rien faire avec sans les deux autres éléments.
- Votre **mot de passe central**, indispensable pour déverrouiller la base de donnée.
- Un **fichier clé**, à conserver en lieu sûr, sur votre ordinateur ou de préférence dans plusieurs clés USB au cas où l'une devient défectueuse.
