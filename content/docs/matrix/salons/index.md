---
title: "Salons Matrix"
description: ""
lead: ""
date: 2021-05-31T11:46:53+02:00
lastmod: 2021-05-31T11:46:53+02:00
draft: false
images: []
menu:
  docs:
    parent: "matrix"
weight: 230
toc: true
---

## Introduction

Les **Salons** dans Element/Matrix sont très similaires aux notions de **Groupes** dans WhatsApp ou Telegram.

N'importe qui peut créer un salon facilement, un salon peut être :

- **Privé et chiffré**, disponible uniquement sur invitation et réservé à un groupe d'ami.
- **Public** et disponible à tout utilisateur possédant le lien du salon, et devenir une sorte de **forum en ligne**.
- **Public**, mais où seuls les utilisateurs choisis peuvent écrire, en faisant une sorte de **fil d'actualité**.

Les salons publics dans Element peuvent même être rendus visibles à des personnes qui ne possèdent pas de compte Matrix.

Grâce au bot Telegram, un **salon Matrix peut être synchronisé avec un groupe Telegram**.

## Créer un nouveau salon

Voyons comment créer un salon :

{{< img src="start-create-room.jpeg" alt="Créer un nouveau salon" caption="Sur ordinateur, cliquer sur le bouton '+' à côté de la liste des salons" class="border-0" >}}

Puis cliquer sur **Créer un nouveau salon**

{{< img-simple src="start-create-room-2.jpeg" alt="Créer un nouveau salon" class="border-0" >}}

À partir de là deux options sont disponibles :

- Un salon **privé**, avec le chiffrement activé ou non ( Activer le chiffrement rendra l'historique illisible pour les nouveaux utilisateurs du salon, et rendra le salon incompatible avec les passerelles ).

{{< img-simple src="create-new-room.jpeg" alt="Créer un nouveau salon" class="border-0" >}}

- Un salon **public**, qui sera accessible par une adresse que vous pourrez choisir.

{{< img-simple src="create-new-public-room.jpeg" alt="Créer un nouveau salon" class="border-0" >}}


Choisissez maintenant un nom et un sujet pour votre salon, ainsi qu'une adresse si il s'agit d'un salon public.

{{< img-simple src="continue-public-room.jpeg" alt="Créer un nouveau salon" class="border-0" >}}

Et le salon est maintenant créé ! Il ne vous reste plus qu'à diffuser son adresse ou d'inviter de nouveaux utilisateurs !

## Inviter dans un salon

Maintenant que votre nouveau salon est créé, vous pouvez commencer à inviter d'autres utilisateurs de Matrix.

{{< img src="informations-sur-le-salon" alt="Créer un nouveau salon" caption="Sur ordinateur, cliquer sur le bouton 'i' en haut à droite une fois dans le salon" class="border-0" >}}

Vous ferez apparaître cet écran :

{{< img src="informations-salon" alt="Créer un nouveau salon" class="border-0" >}}

À partir de là, vous pouvez :

- Cliquer sur **partager le salon**, vous arriverez ainsi sur un nouvel écran où vous pourrez copier l'adresse Matrix du salon, afficher un QR code qu'un autre utilisateur pourra scanner pour rejoindre le salon, où envoyer l'adresse par mail ou autre plate-forme.

{{< img src="partager-le-salon" alt="Créer un nouveau salon" class="border-0" >}}

- Afficher la liste des personnes participant au salon en cliquant sur **personnes**, vous obtiendrez ainsi la liste des participants.

{{< img src="utilisateurs-du-salon" alt="Créer un nouveau salon" class="border-0" >}}

De là il suffit de cliquer sur **inviter dans ce salon**, et sur le nouvel écran, rechercher un utilisateur parmi ceux que vous connaissez, ou saisir son adresse Matrix.

{{< img src="find-user" alt="Créer un nouveau salon" class="border-0" >}}

Une fois le ou les utilisateur(s) sélectionné(s) en cliquant dessus, cliquez sur **Inviter**.

{{< img src="utilisateur-invité" alt="Créer un nouveau salon" class="border-0" >}}

L'utilisateur apparaîtra dans la liste des invités jusqu'à ce qu'il·elle accepte l'invitation.


## Gérer les notifications

Dans la liste des salons, à côté de chaque salon se tient une petite icône en forme de cloche :

{{< img-simple src="param-notifs" alt="Notifications" class="border-0" >}}

Cette icône sert à régler les notifications du salon, cliquez dessus pour régler les paramètres de notification du salon.

{{< img-simple src="menu-notifs" alt="Notifications" class="border-0" >}}

- **Utiliser la valeur par défaut** : utiliser le réglage global de l'application réglé dans les paramètres de notifications ( généralement équivalent à **tous les messages** ).
- **Tous les messages** : recevoir une notification pour tous les messages envoyés dans le salon.
- **Mentions et mots-clés** : recevoir une notification uniquement lorsque votre nom est mentionné, ou un mot-clé dans une liste réglable dans les paramètres de notifications.
- **Aucun** : couper les notifications pour ce salon.

## Trucs et astuces

### Changer son nom d'utilisateur dans un salon spécifique.

Dans Element, vous pouvez régler votre nom d'utilisateur tel qu'il apparaîtra dans un salon spécifique.
Il suffit, en utilisant **Element sur ordinateur, web ou bureau**, en étant dans le salon où vous souhaitez changer votre nom affiché, de taper:</br>
`/myroomnick Mon nom pour ce salon`
</br>Et envoyer le message.
