---
title: "Synchroniser Nextcloud depuis son ordinateur"
description: ""
lead: ""
date: 2021-06-02T17:25:16+02:00
lastmod: 2021-06-02T17:25:16+02:00
draft: false
images: []
menu:
  docs:
    parent: "nextcloud"
weight: 330
toc: true
---

## Synchroniser vos fichiers avec le Cloud

Premièrement, rendez vous sur https://nextcloud.com/fr_FR/install/#install-clients pour installer l'application de synchronisation bureau Nextcloud.

{{< img src="nextcloud-download.jpeg" alt="Cloud Alternumerica" class="border-0" >}}

Téléchargez l'application correspondant à votre environnement de travail ( Windows, MacOS ou Linux ) et installez le programme.

<div class="alert alert-warning" role="alert">
Le processus d'installation est complètement relatif à votre environnement de travail, il est difficile d'en décrire toute la démarche ici.
</div>

Une fois le programme installé, lancez le logiciel.

{{< img src="se-connecter-a-nextcloud.png" alt="Cloud Alternumerica" class="border-0" >}}

Cliquez sur **Se connecter à Nextcloud**

{{< img src="adresse-du-serveur.png" alt="Cloud Alternumerica" class="border-0" >}}

Sur l'écran suivant, saisissez simplement l'adresse du serveur Nextcloud d'Alternumerica : **cloud.alternumerica.org**

Puis cliquez sur **Suivant**.

{{< img src="bascule-navigateur.png" alt="Cloud Alternumerica" class="border-0" >}}

Nextcloud va maintenant vous demander de basculer sur votre navigateur internet pour vous connecter à votre compte Nextcloud.

{{< img src="se-connecter.jpg" alt="Cloud Alternumerica" class="border-0" >}}

Cette fenêtre devrait apparaître, cliquez sur **Se connecter**.

{{< img src="Authentification-unique-Alternumerica.jpg" alt="Cloud Alternumerica" class="border-0" >}}

Sur l'écran suivant, choisissez bien l'option : **Authentification unique Alternumerica**

Vous serez redirigé vers le serveur d'authentification de Alternumerica :

{{< img src="login-alternumerica.png" alt="Cloud Alternumerica" class="border-0" >}}

Saisissez vos identifiants Alternumerica, puis cliquez sur **Connexion**.

Vous serez alors redirigé de nouveau sur cloud.alternumerica.org :

{{< img src="Autoriser-acces.jpg" alt="Cloud Alternumerica" class="border-0" >}}

Cliquez simplement sur **Autoriser l'accès**.

{{< img src="compte-connecté.jpg" alt="Cloud Alternumerica" class="border-0" >}}

Votre compte est maintenant connecté, vous pouvez **fermer votre navigateur**.

Cela devrait vous ramener sur le logiciel de synchronisation Nextcloud :

{{< img src="sync-folders.png" alt="Cloud Alternumerica" class="border-0" >}}

Sur cet écran vous pouvez choisir le dossier qui sera synchronisé avec votre Cloud. Par défaut le logiciel créera un nouveau dossier **Nextcloud** sur votre ordinateur. Mais vous pouvez changer ce dossier. Si vous voulez changer de dossier, veillez à bien sélectionner un dossier vide.

Pour faire au plus simple : **Décochez "Ask before syncing external storages"** de manière à ce que Nextcloud synchronise automatiquement les dossiers de groupe auxquels vous avez accès ( des dossiers partagés par un groupe sur le Cloud ).
Vous pouvez aussi plus tard [synchroniser les dossiers de groupe manuellement](#synchroniser-les-dossiers-de-groupe).

Et **cliquez simplement sur Connexion**.

{{< img src="icone-nextcloud.png" alt="Cloud Alternumerica" class="border-0" >}}

Une petite icône devrait apparaître sur la barre d'outils de votre ordinateur. Nextcloud va maintenant synchroniser vos dossiers, et tout nouveau fichier ou dossier ajouter sur votre ordinateur sera automatiquement synchronisé avec le Cloud !

### Synchroniser les dossiers de groupe

Certains dossiers sur Nextcloud ne sont pas votre propriété mais sont partagés pour un groupe d'utilisateurs. Selon les droits qui vous sont accordés, vous pouvez simplement les lire, ou les modifier. Le logiciel de synchronisation Nextcloud ne synchronise pas ces dossiers par défaut, nous allons voir comment activer la synchronisation pour ces dossiers :

Vous pouvez faire apparaître le menu Nextcloud en **cliquant sur l'icône de synchronisation**.

{{< img src="interface-nextcloud.png" alt="Cloud Alternumerica" class="border-0" >}}

Cliquez en haut à gauche du menu sur votre utilisateur pour faire apparaître un sous-menu contenant les paramètres.

{{< img src="parametres.png" alt="Cloud Alternumerica" class="border-0" >}}

Cliquez sur **paramètres**.

{{< img src="dossier-groupe.png" alt="Cloud Alternumerica" class="border-0" >}}

Vous arriverez sur cette interface, vous prévenant que certains dossiers n'ont pas été synchronisés.

{{< img src="sync-dossier-groupe.png" alt="Cloud Alternumerica" class="border-0" >}}

**Cochez le dossier** de groupe vous intéressant, ici *alternumerica*, puis cliquez sur **Appliquer**.

{{< img src="sync-OK.png" alt="Cloud Alternumerica" class="border-0" >}}

Terminé !
Nextcloud va maintenant synchroniser ce dossier et toutes les modifications qui y seront faites !
