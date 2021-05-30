---
title: "Première connexion à Element"
description: ""
lead: ""
date: 2021-05-28T16:39:37+02:00
lastmod: 2021-05-28T16:39:37+02:00
draft: false
images: []
menu:
  docs:
    parent: "matrix"
weight: 220
toc: true
---


## Depuis votre navigateur internet
#### ( Firefox, Chrome, Edge )


Saisissez l'adresse de l'application en ligne [Element](https://element.alternumerica.org) :
[https://element.alternumerica.org](https://element.alternumerica.org)


{{< img src="element.alternumerica.org-accueil.jpeg" alt="Square" class="border-0" >}}


Cliquez ensuite sur le bouton **Se connecter**

Vous devriez atterrir sur l'écran de connexion suivant :

{{< img src="element.alternumerica.org-connexion.jpeg" alt="Square" class="border-0" >}}

Pour utiliser votre compte Alternumerica pour la connexion, cliquez sur **Se connecter avec l'authentification unique**

{{< img src="connexion-auth-unique.jpeg" alt="Square" class="border-0" >}}

Vous serez dirigé vers l'écran de connexion de Alternumerica :

{{< img src="login.alternumerica.org-connexion.jpeg" alt="Square" class="border-0" >}}

Utilisez les identifiants qui vous ont été communiqués pour vous connecter.

Si cela est votre première connexion aux serveurs d'Alternumerica, vous serez demandé de remplir quelques informations, et de changer votre mot de passe.
Conservez ce mot de passe en lieu sûr !

Une fois vos informations remplies, vous serez normalement dirigés vers le menu principal d'Element

{{< img src="element.alternumerica.org-welcome.jpeg" alt="Square" class="border-0" >}}

Il vous restera à accepter les notifications et le stockage persistant sur votre navigateur pour que l'application en ligne fonctionne correctement.

<div class="alert alert-success" role="alert">
N'oubliez maintenant pas d'ajouter la page aux favoris de votre navigateur pour retrouver facilement Element, et de <a href="#configuration-de-la-sauvegarde-s%C3%A9curis%C3%A9e">configurer la sauvegarde sécurisée</a>
</div>

## Depuis l'application PC

Télécharger l'application PC rend l'utilisation d'Element plus accessible, de l'ouvrir sans avoir besoin de passer par son navigateur internet ( Firefox, Google Chrome ou Edge ), et d'avoir une notification sur le bureau lors de la récéption d'un message.

{{< img src="element-icon-on-desktop.jpeg" alt="Square" class="border-0" >}}

Commencez par vous rendre sur le site d'internet d'Element pour télécharger le logiciel : https://element.io/get-started
Et cliquez sur le bouton de téléchargement correspondant à votre ordinateur.

{{< img src="element-download.jpeg" alt="Square" class="border-0" >}}

Ou bien cliquez sur un des liens de téléchargement direct :
- [Pour Windows](https://packages.riot.im/desktop/install/win32/x64/Element%20Setup.exe)
- [Pour Mac](https://packages.riot.im/desktop/install/macos/Element.dmg)

Une fois le téléchargement terminé, lancez l'installation, autorisez l'application à s'installer, et suivez les instructions pour procéder à l'installation.

Une fois le logiciel installé, lancez le. Vous devriez arriver sur cet écran :

{{< img src="element-desktop-accueil.jpeg" alt="Square" class="border-0" >}}

Cliquez sur **Se connecter** pour atterrir sur cet écran :

{{< img src="element-desktop-connexion.jpeg" alt="Square" class="border-0" >}}

La première chose à faire est de configurer le logiciel pour qu'il se connecte à Alternumerica plutôt qu'aux serveurs de Matrix.org. Il faut pour cela cliquer sur le lien **"modifier"** comme encadré en rouge sur la photo ci-dessus.

Sur l'écran suivant vous pouvez changer le serveur d'accueil. Comme sur la photo ci-dessous, saisissez l'adresse du serveur Matrix d'Alternumerica : **synapse.alternumerica.org**.

{{< img src="element-change-server.jpeg" alt="Square" class="border-0" >}}

Puis cliquez sur **Continuer**.

Vous devriez être de retour sur l'écran de connexion, et un nouveau bouton **Se connecter avec l'authentification unique** devrait être apparu.

{{< img src="element-desktop-connexion-alternumerica.jpeg" alt="Square" class="border-0" >}}

Cliquez dessus, un lien devrait s'ouvrir dans votre navigateur, vous dirigeant vers le site de connexion d'Alternumerica.
Saisissez les identifiants, nom d'utilisateur et mot de passe qui vous ont été confiés.

{{< img src="login.alternumerica.org-connexion.jpeg" alt="Square" class="border-0" >}}

Si vous entrez ces identifiants pour la première fois, il vous sera demandé de choisir un nouveau mot de passe et de rentrer quelques informations.

Une fois cela fait, vous serez redirigé vers cette page :

{{< img src="continue-to-your-account.jpeg" alt="Square" class="border-0" >}}

Cliquez simplement sur **Continue** pour être renvoyé sur votre application Element connectée à votre compte Matrix/Alternumerica.

Vous devriez maintenant être sur le menu principal d'Element.

{{< img src="element-desktop-welcome.jpeg" alt="Square" class="border-0" >}}

<div class="alert alert-success" role="alert">
N'oubliez maintenant pas de configurer Element pour se <a href="#configurer-element-pour-se-lancer-au-d%C3%A9marrage">lancer au démarrage</a>, et de <a href="#configuration-de-la-sauvegarde-s%C3%A9curis%C3%A9e">configurer la sauvegarde sécurisée</a>
</div>


### Configurer Element pour se lancer au démarrage

Cliquez sur votre nom d'utilisateur en haut à gauche de l'écran :

{{< img src="element-desktop-menu.jpeg" alt="Square" class="border-0" >}}

Cela fera apparaître un menu, cliquez sur **Tous les paramètres**.

{{< img src="element-menu-display.jpeg" alt="Square" class="border-0" >}}

Dans le menu apparu, ouvrez le sous-menu **Préférences**

{{< img src="element-menu-preferences.jpeg" alt="Square" class="border-0" >}}

De là cherchez la section **Démarrer automatiquement après la phase d'authentification du système**, veuillez à ce que l'interrupteur soit sur la position verte comme sur la photo :

{{< img src="element-desktop-demarrer-automatiquement.jpeg" alt="Square" class="border-0" >}}


## Depuis l'application Android

<div class="alert alert-warning" role="alert">
Malheureusement, l'application Element sur Android n'est pour l'instant pas capable de gérer plusieurs comptes Matrix. Si vous possédez déjà un compte Matrix, vous pouvez utilisez ce compte avec <a href="https://fluffychat.im/">FluffyChat</a>, disponible sur le <a href="https://play.google.com/store/apps/details?id=chat.fluffy.fluffychat">PlayStore</a> ou sur <a href="https://fluffychat.im/en/fdroid.html">F-Droid</a>.
</div>

Une fois l'application [Element](https://element.io/get-started) téléchargée et installée sur [PlayStore](https://play.google.com/store/apps/details?id=im.vector.app) ou [F-Droid](https://f-droid.org/packages/im.vector.app/), ouvrez la.

{{< img-simple src="resized_element-android-start.png" alt="Element-android" class="border-0 mx-auto d-block" >}}

Cliquez simplement sur **Démarrer**.

{{< img-simple src="resized_element-android-choose-server.png" alt="Element-android" class="border-0 mx-auto d-block" >}}

L'application vous demande de choisir un serveur.

<div class="alert alert-warning" role="alert">
 👉 <i>N'oubliez pas ! Element et Matrix reposent sur une architecture décentralisée, vous pouvez choisir vous-même à qui confier vos données ! Même si cela semble compliqué à premier abord, c'est la possibilité de ce choix qui fait tout l'attrait d'Element/Matrix !</i>
</div>

Vous allez donc maintenant choisir **Autre**, *Paramètres personnalisés et avancés* pour atterrir sur cet écran :

{{< img-simple src="resized_element-android-address-server.png" alt="Element-android" class="border-0 mx-auto d-block" >}}

C'est ici que vous pouvez saisir l'adresse du serveur Matrix de Alternumerica : **synapse.alternumerica.org**.

Cliquez ensuite sur **Poursuivre**.

{{< img-simple src="resized_element-android-auth-unique.png" alt="Element-android" class="border-0 mx-auto d-block" >}}

Cliquez ensuite sur **Poursuivre avec authentification unique** pour utiliser vos identifiants Alternumerica.

Vous serez alors dirigés vers votre navigateur internet vers cette page :

{{< img-simple src="resized_element-android-keycloak-connexion.png" alt="Element-android" class="border-0 mx-auto d-block" >}}

Saisissez vos identifiants Alternumerica avant de valider avec le bouton **Connexion**.

{{< img-simple src="resized_element-android-keycloak-continue.png" alt="Element-android" class="border-0 mx-auto d-block" >}}

Et cliquez sur **Continue** pour confirmer l'accès de l'application à votre compte.
Votre téléphone Android vous demandera peut-être avec quelle application continuer, choisissez bien sûr **Element**.

Vous devriez maintenant être connecté à votre compte Element.

<div class="alert alert-success" role="alert">
N'oubliez maintenant pas de <a href="#configuration-de-la-sauvegarde-s%C3%A9curis%C3%A9e">configurer la sauvegarde sécurisée</a> si c'est votre première connexion, ou de <a href="#v%C3%A9rification-dune-nouvelle-session">vérifier votre session</a> si vous avez déjà une autre session connectée à votre compte.
</div>

## Configuration de la sauvegarde sécurisée

<div class="alert alert-danger" role="alert"><b>La sauvegarde sécurisée est indispensable pour retrouver vos messages d'un appareil à l'autre.</b></div>

Une fois votre première conversation lancée, Element va vous demander de configurer la sauvegarde sécurisée.

{{< img src="element-configurer-sauvegarde-sécurisée.jpeg" alt="Square" class="border-0" >}}

<div class="alert alert-warning" role="alert">
 👉 <i>La sauvegarde sécurisée permet de transférer les clés de chiffrement d'un appareil à l'autre de manière sécurisée.
Les développeurs d'Element et de Matrix sont arrivés à une solution suffisamment simple et ingénieuse pour que la sécurité des messages ne puisse pas être mise en cause par qui que ce soit, pas même par l'administrateur du système : Cela apporte la rare garantie que seul vous et votre correspondant êtes capables de lire les messages que vous échangez.
Et tout cela sans dépendre d'une instance centrale pour gérer vos clés comme c'est le cas de la plupart des messageries instantanées.</i>
</div>

Cliquez sur **Continuer** sur la bulle apparue en haut à gauche de votre écran.

{{< img src="element-configurer-sauvegarde-sécurisée-configure.jpeg" alt="Square" class="border-0" >}}

Element va vous demander de **Générer une clé de sécurité** ou de Saisir une phrase de sécurité, la première option est la plus simple, cliquez simplement sur **Continuer**.

{{< img src="element-configurer-sauvegarde-sécurisée-sauvegarde.jpeg" alt="Square" class="border-0" >}}

Vous allez maintenant devoir sauvegarder votre clé en lieu sûr, idéalement dans un **gestionnaire de mots de passe**, sinon dans un **dossier privé** que vous êtes sûr de conserver. Vous pouvez aussi le conserver sur votre Cloud, mais cela est moins conseillé.

{{< img src="element-configurer-sauvegarde-sécurisée-auth.jpeg" alt="Square" class="border-0" >}}

Vous allez maintenant devoir confirmer votre identité avec l'**authentification unique**. Vous serez normalement dirigé vers cette page de sécurité :

{{< img src="element-configurer-sauvegarde-sécurisée-keycloak-continue.jpeg" alt="Square" class="border-0" >}}

Confirmez simplement en cliquant sur **Continue with Serveur Keycloak**

{{< img src="element-configurer-sauvegarde-sécurisée-confirm.jpeg" alt="Square" class="border-0" >}}

Et cliquez enfin sur **Confirmer** pour confirmer la configuration du chiffrement.


## Vérification d'une nouvelle session

Tout **nouvel appareil** ou **nouvelle application** se connectant à votre compte Matrix est considéré comme une **nouvelle session**.

<div class="alert alert-warning" role="alert">
 👉 <i>Toujours dans la logique d'offrir le système le plus sécurisé et le plus indépendant d'une instance centrale possible, ce système de vérification permet d'échanger vos clés de chiffrement entre appareils, et ainsi d'accéder aux messages chiffrés d'un appareil à l'autre. En ne procédant pas à cette vérification, vos appareils et sessions n'auront pas accès aux messages privés reçus sur d'autres sessions.</i>
</div>

Lorsque vous vous connectez à votre compte Matrix avec une nouvelle application, vous verrez normalement ce type d'alerte sur vos appareils :

{{< img src="element-verifier-connexion.jpeg" alt="Square" class="border-0" >}}

{{< img-simple src="demande-verification.png" alt="Square" class="border-0 mx-auto" >}}

{{< img-simple src="resized_element-android-verify-session.png" alt="Square" class="border-0 mx-auto" >}}

À partir de là vous sera proposé deux solutions :

- Vérifier votre session à partir de la clé que vous avez configuré lors de la [sauvegarde sécurisée](#configuration-de-la-sauvegarde-s%C3%A9curis%C3%A9e).

{{< img-simple src="verifier-avec-cle-securite.jpeg" alt="Verifier avec clé de sécurité" class="border-0 mx-auto" >}}

- Vérifier votre session depuis un autre appareil, ce qui est de loin la solution la plus simple :

{{< img-simple src="element-scan-code.jpeg" alt="Verifier avec clé de sécurité" class="border-0 mx-auto" >}}

Et là à nouveau ! Deux solutions sont proposées !

- La plus simple, scanner un code QR. Sauf que cela ne fonctionne généralement que d'un **ordinateur à un téléphone**, ou cas plus exceptionnel peut-être, d'un téléphone à un autre.

{{< img-simple src="verifier-scan-code.png" alt="Verifier avec clé de sécurité" class="border-0 mx-auto d-block" >}}

Il suffit alors de scanner le code QR d'un appareil avec l'autre appareil !

- L'autre solution, utile surtout lorsque les **deux sessions se trouvent sur le même appareil**, vérifier la correspondance d'émojis qui s'affichent à l'écran.

{{< img-simple src="emojis-verification.jpeg" alt="Verifier avec clé de sécurité" class="border-0 mx-auto d-block" >}}

{{< img-simple src="verifier-emojis.png" alt="Verifier avec clé de sécurité" class="border-0 mx-auto d-block" >}}

Vérifier que les émojis correspondent et cliquez sur les **deux sessions, "ils correspondent"**.

{{< img-simple src="element-verifié.jpeg" alt="Verifier avec clé de sécurité" class="border-0 mx-auto d-block" >}}

{{< img-simple src="verifier-OK.png" alt="Verifier avec clé de sécurité" class="border-0 mx-auto d-block" >}}

Et voilà ! Le travail est fait ! Votre nouvelle session est maintenant vérifiée !

<div class="alert alert-warning" role="alert">
 👉 <i>Cette vérification peut sembler inutile, bizarre et rébarbative, mais c'est en réalité un moyen simple et ingénieux d'intégrer une vérification de sécurité qui protège à la fois du piratage, et de l'ingérence potentielle d'un administrateur serveur.</i>
</div>
