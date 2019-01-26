---
id: 3064
title: Failles de sécurité majeures sur les processeurs Intel
date: 2018-01-10T09:39:02+00:00
author: Kenneth Hounsou
layout: post
guid: https://ino-tech.net/?p=3064
permalink: /faille-de-securite-processeurs-intel.html
better-views-count:
  - "136"
bs_featured_image_credit:
  - ""
page_layout:
  - default
post_template:
  - default
single_excerpt_type:
  - default
post_comments:
  - default
post_breadcrumb:
  - default
bs_subtitle:
  - ""
wps_subtitle:
  - ""
bs_social_share_facebook:
  - "17"
bs_social_share_twitter:
  - "0"
bs_social_share_interval:
  - "1535305523"
onesignal_meta_box_present:
  - "1"
onesignal_send_notification:
  - ""
image: /wp-content/uploads/2018/01/code_meltdown_spectre_2.jpg
categories:
  - Constructeurs
  - Tech
tags:
  - AMD
  - AR
  - bug
  - CPU
  - faille
  - Intel
  - Meltdown
  - processeur
  - ralentissement
  - Spectre
---
La nouvelle année commence en trombe dans le domaine de la sécurité informatique. En effet, deux failles de sécurité majeures affectant les processeurs ont déjà été découvertes. Il ne s&rsquo;agit pas seulement de [processeurs Intel](https://ino-tech.net/nouvelle-gamme-de-processeurs-intel-fera-sauter-de-joie-les-gameurs.html) mais aussi de puces AMD et ARM.

[<img class=" wp-image-3093 aligncenter" src="https://ino-tech.net/wp-content/uploads/2018/01/amd-intel-processeurs-300x188.jpg" alt="" width="482" height="302" srcset="https://inotech008.000webhostapp.com/wp-content/uploads/2018/01/amd-intel-processeurs-300x188.jpg 300w, https://inotech008.000webhostapp.com/wp-content/uploads/2018/01/amd-intel-processeurs-768x480.jpg 768w, https://inotech008.000webhostapp.com/wp-content/uploads/2018/01/amd-intel-processeurs.jpg 840w" sizes="(max-width: 482px) 85vw, 482px" />](https://ino-tech.net/wp-content/uploads/2018/01/amd-intel-processeurs.jpg)

## Des failles de sécurité historiques

La première faille, surnomée « Meltdown », ne concerne que les [processeurs Intel](https://ino-tech.net/nouvelle-gamme-de-processeurs-intel-fera-sauter-de-joie-les-gameurs.html). La deuxième, quant à elle, surnomée « Spectre », a touché les puces Intel, AMD et ARM. Autrement dit, tous les systèmes d&rsquo;exploitation (Windows, MacOS, Linux et Android) sont à priori menacés.

L&rsquo;attaque Spectre permet à un logiciel malveillant d&rsquo;accéder aux informations d’un autre logiciel sans autorisation. Il y arrive en forçant le processeur à exécuter une commande qu’il ne ferait pas en temps normal. Cependant, Meltdown reste la plus dangereuse des deux failles de sécurité, car donnant accès au noyau de l&rsquo;ordinateur.

## <span style="font-weight: 400;">Meltdown en question</span>

<span style="font-weight: 400;">La faille est plutôt considérable, car il s&rsquo;agit d&rsquo;un bug matériel qui affecterait tous les processeurs Intel sur le marché depuis au moins 10 ans. En effet, ce bug permet aux programmes utilisateurs normaux d&rsquo;accéder à la mémoire protégée du noyau. La mise à jour du <a href="https://fr.wikipedia.org/wiki/Microprogrammation">microcode</a> des processeurs ne pouvant faire disparaître le problème comme par enchantement, les concepteurs de systèmes d&rsquo;exploitation s’attèlent à retravailler certaines fonctionnalités pour le contourner.<br /> </span>

## <span style="font-weight: 400;">Petite leçon sur le noyau<br /> </span>

<span style="font-weight: 400;">C&rsquo;est le noyau qui contrôle l&rsquo;interaction entre les applications et le système de fichiers. Étant le cœur du système d&rsquo;exploitation, il a à charge les tâches les plus sensibles d&rsquo;un ordinateur. C&rsquo;est essentiellement lui qui va permettre à un programme de lire et d&rsquo;écrire des fichiers. Il gère également la mémoire et les périphériques, tels que le clavier et l&rsquo;appareil photo. En d&rsquo;autres termes, sur un ordinateur, le noyau est une pièce vitale. </span>

[<img class=" wp-image-3094 aligncenter" src="https://ino-tech.net/wp-content/uploads/2018/01/Architecture_noyau-monolithique-300x144.png" alt="" width="482" height="231" srcset="https://inotech008.000webhostapp.com/wp-content/uploads/2018/01/Architecture_noyau-monolithique-300x144.png 300w, https://inotech008.000webhostapp.com/wp-content/uploads/2018/01/Architecture_noyau-monolithique.png 675w" sizes="(max-width: 482px) 85vw, 482px" />](https://ino-tech.net/wp-content/uploads/2018/01/Architecture_noyau-monolithique.png)

<span style="font-weight: 400;">Cela veut donc dire qu&rsquo;avec ce genre de failles de sécurité, un programme quelconque peut tout simplement, s’il inclut les routines qu’il faut, accéder à vos ressources critiques sans avoir à faire face à des remparts. Vous convenez bien qu&rsquo;avoir un noyau compromis est un risque qu&rsquo;on ne veut pas prendre. </span>

## <span style="font-weight: 400;">Faut-il s&rsquo;alarmer face à ces failles de sécurité ?</span>

<span style="font-weight: 400;">Sachez que Microsoft, Apple ainsi que les développeurs qui travaillent sur le noyau Linux s’attèlent à trouver une solution concernant Meltdown. Néanmoins, il faut noter que les processeurs Intel connaîtront un ralentissement dans l&rsquo;activité en raison des correctifs qui seront apportés<strong>. </strong>On parle là, pour les ordinateurs équipés de puces Intel, d’un ralentissement de 5 à 30%<strong>. </strong></span><span style="font-weight: 400;">Pour la faille Spectre, le problème reste difficile, et aucune mesure claire n&rsquo;a encore été trouvée pour l&rsquo;éliminer.</span><span style="font-weight: 400;"><br /> </span>