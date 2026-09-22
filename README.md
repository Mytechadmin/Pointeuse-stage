# ⏱ Pointeuse – Suivi d’horaires de travail

Application web légère de pointage horaire avec calcul automatique du solde hebdomadaire (base 35 h).

## Fonctionnalités

- Pointage en un clic (arrivée / départ)
- Ajout et modification manuelle des créneaux
- Calcul en temps réel :
  - Aujourd’hui
  - Semaine en cours
  - Solde vs 35 h (vert = positif, rouge = négatif)
  - Mois en cours
- Résumé détaillé de la semaine (mis en avant le vendredi)
- Historique groupé par semaine
- Semaines terminées **repliables** et **verrouillées** (lecture seule)
- Sauvegarde locale (localStorage)
- Export / Import JSON
- Sauvegarde automatique sur le PC (File System Access API)


## Objectif

Outil personnel pour suivre mon temps de travail pendant un stage / alternance de 4 mois, avec un bilan clair chaque vendredi.

## Stack

- HTML / CSS / JavaScript vanilla (aucune dépendance)
- Fonctionne 100 % côté client

## Utilisation

Ouvre simplement `index.html` dans un navigateur moderne (Chrome, Edge, Brave recommandés pour la sauvegarde auto sur PC).

## Note sur le développement

Ce projet a été réalisé avec l’assistance d’une IA (Grok).  
J’ai défini le besoin, itéré sur les fonctionnalités (solde 35 h, verrouillage des semaines passées, historique dépliable, etc.) et validé chaque évolution jusqu’à obtenir exactement le comportement souhaité.

## Aperçu

<!-- Mets ici tes captures d’écran -->
