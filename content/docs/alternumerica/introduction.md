---
title: "Introduction"
description: "Vos premiers pas avec Alternumerica !"
lead: ""
date: 2021-05-28T16:50:06+02:00
lastmod: 2021-05-28T16:50:06+02:00
draft: false
images: []
menu:
  docs:
    parent: "alternumerica"
weight: 110
toc: true
---

### Les services d'Alternumerica

Pour obtenir de l'aide : {{< email user="assistance" domain="alternumerica.org" >}}

Pour gérer votre compte Alternumerica : https://login.alternumerica.org/auth/realms/Alternumerica/account/#/


Pour toute assistance :

<script src="https://code.jquery.com/jquery-2.1.4.min.js"></script>

<button id="feedback-form">Demande d'assistance</button>

<script id="zammad_form_script" src="https://zammad.alternumerica.org/assets/form/form.js"></script>

<script>
$(function() {
  $('#feedback-form').ZammadForm({
    messageTitle: 'Formulaire d\'assistance',
    messageSubmit: 'Envoyer',
    messageThankYou: 'Merci pour votre requête  (#%s) ! Nous vous recontacterons dans les meilleurs délais.',
    showTitle: true,
    modal: true,
    attachmentSupport: true
  });
});
</script>
