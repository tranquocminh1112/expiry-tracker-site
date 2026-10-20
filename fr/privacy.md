---
title: Politique de confidentialité
layout: default
lang: fr
page_id: privacy
permalink: /fr/privacy
---

# Politique de confidentialité — Rappel de péremption

_Mise à jour : 19 octobre 2026_

> Cette page est une traduction fournie à titre de référence uniquement. **La [version vietnamienne](/privacy) fait foi et a valeur légale.** En cas de divergence, le texte vietnamien prévaut.

**Rappel de péremption** (« l'application ») vous aide à enregistrer les dates limites des aliments et d'autres choses à la maison (médicaments, bons d'achat, points de fidélité, cartes SIM, papiers…) et vous prévient avant l'échéance. Elle garde aussi la trace des objets sans date limite et de l'endroit où les choses sont rangées. Elle est conçue de sorte que **le développeur ne collecte pas et ne peut pas voir vos données**.

## Ce que l'application stocke

- Noms des articles, catégories, quantités, unités, dates de péremption (ou « Sans date limite »), **emplacements** (par exemple « frigo » ou « garage »), notes, historique d'utilisation (y compris la liste d'où un article a été déplacé).
- La valeur que vous notez pour un bon, des points de fidélité ou une SIM : un montant ou un nombre de points, avec sa devise ou la mention « points ».
- Les **photos** que vous ajoutez aux articles (une par article) et une miniature de chacune. Les photos sont réduites sur votre appareil, et **toutes les informations jointes à l'image, y compris le lieu de la prise de vue (GPS, EXIF), sont supprimées** avant l'enregistrement.
- Le nom ou pseudonyme que vous saisissez, affiché à côté des articles que vous ajoutez ou utilisez dans les listes partagées. Lorsque vous invitez quelqu'un, ce nom est inclus dans l'invitation.
- Les paramètres de rappel (heure de rappel), stockés sur votre appareil.

## Où les données sont stockées

- Sur votre iPhone et dans **votre propre compte iCloud** (Apple CloudKit) pour synchroniser vos appareils. Le développeur n'a aucun accès à votre iCloud.
- Les noms d'articles, notes, emplacements, noms de listes, noms des auteurs et les montants ou points que vous notez sont **chiffrés** sur les serveurs iCloud avec des clés appartenant à votre compte.
- Les **photos** sont stockées dans l'iCloud du **propriétaire de la liste** (la personne qui a créé la liste contenant l'article) et comptent dans son stockage iCloud : votre iCloud pour vos listes, celui de l'autre personne pour une liste qu'elle partage avec vous. Les photos et miniatures **peuvent ne pas être chiffrées de bout en bout** comme les informations ci-dessus : elles restent protégées par la protection standard des données d'iCloud (chiffrement en transit et au repos sur les serveurs d'Apple), mais les clés peuvent être gérées par Apple. Si cela vous importe, ne photographiez pas de documents contenant des informations sensibles.
- Lorsque vous **partagez une liste**, vous choisissez pour chaque personne si elle peut **modifier** ou seulement **consulter**. Elle voit tout le contenu de cette liste, y compris les emplacements et les photos, ainsi que les noms des personnes ayant ajouté ou utilisé des articles. Vous pouvez arrêter le partage ou retirer une personne à tout moment.

## Ce que l'application ne fait pas

- Pas de compte séparé, pas de connexion en dehors d'iCloud.
- Pas de publicité, pas de suivi, pas d'outils d'analyse ou de collecte de données tiers.
- Aucune vente ni partage de données avec qui que ce soit.
- Les suggestions de catégorie pendant la saisie d'un nom se font **sur votre appareil** : elles s'appuient sur les articles déjà présents dans vos listes, sur une table de mots-clés intégrée à l'app et, sur les appareils dotés d'Apple Intelligence, sur le modèle de langage d'Apple qui fonctionne sur l'appareil. Les noms ne sont envoyés ni au développeur ni à aucun serveur.

## Appareil photo et photothèque

L'application n'utilise l'appareil photo que lorsque vous touchez **Prendre une photo** pour photographier un article. Quand vous choisissez une photo dans votre photothèque, iOS ne transmet à l'application que la photo choisie ; l'application ne peut pas voir votre photothèque. Les photos ne sont envoyées ni au développeur ni à aucun serveur autre qu'iCloud, comme décrit ci-dessus.

## Signalement de bug

En appuyant sur **« Envoyer un rapport de bug »**, l'application ouvre un e-mail prérempli à destination du développeur contenant les versions de l'application et d'iOS, le modèle de l'appareil, l'état d'iCloud et des notifications, le **nombre** de listes et d'articles, ainsi que des codes d'erreur techniques récents. L'e-mail ne contient aucun nom d'article, note ou nom de personne. Vous pouvez le relire et le modifier ; il n'est envoyé que lorsque vous appuyez sur Envoyer.

Il indique aussi votre région, votre fuseau horaire et la langue de l’app, pour savoir si un problème vient du format de date ou d’une traduction.

## Export des données

Lorsque vous touchez **Réglages → Exporter les données (CSV)**, l’app crée sur votre appareil un fichier CSV avec tous les articles que vous voyez : nom de la liste, nom de l’article, quantité, unité, date de péremption, note, **le nom de la personne qui l’a ajouté**, la date d’ajout, la catégorie, la valeur et **l’emplacement**. Le fichier ne contient aucune photo. Le fichier ne quitte votre appareil que si vous choisissez où l’envoyer ou l’enregistrer : réfléchissez avant de partager le fichier d’une liste partagée.

## Notifications

Les notifications de rappel sont générées **localement sur votre appareil** et ne transitent par aucun serveur du développeur.

## Suppression des données

Allez dans **Réglages → Supprimer toutes les données** pour supprimer chaque liste, article (photos et emplacements compris) et entrée d'historique sur l'appareil et dans votre iCloud (les listes que vous partagez sont également supprimées chez les invités). Vous pouvez aussi supprimer des articles individuels, des listes individuelles, ou supprimer l'application. Les données iCloud peuvent être supprimées dans **Réglages → [votre nom] → iCloud → Gérer le stockage**.

## Enfants

L'application ne s'adresse pas aux enfants de moins de 13 ans et ne collecte pas sciemment leurs informations.

## Contact

support@minhtran.io.vn
