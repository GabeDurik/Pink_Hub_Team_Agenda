# Pink Hub — Team Agenda

> **Statut : LEGACY / MIGRATION SOURCE.** Ce dépôt est conservé comme prototype historique. Les évolutions fonctionnelles destinées à l’agenda collectif sont désormais à router vers `GabeDurik/LYRA_MapOS`, dont le périmètre inclut le module Agenda.

Prototype web mobile-first de coordination d’équipe pour les projets artistiques, culturels et associatifs.

L’application permet à chaque membre d’indiquer ses disponibilités, de visualiser les créneaux communs et de préparer un agenda collectif piloté par l’équipe.

## Rôle historique

Ce prototype a précédé l’architecture actuelle de LYRA. Il reste utile comme source de concepts, d’interface et de logique fonctionnelle à auditer avant réintégration éventuelle dans le module Agenda de LYRA.

Le dépôt ne doit pas être fusionné brutalement avec LYRA : les éléments encore utiles doivent être migrés ou réimplémentés de manière ciblée, avec provenance conservée.

> **Confidentialité de la démo publique :** les membres, rôles opérationnels, créneaux et notes inclus dans `index.html` sont des données fictives de démonstration. Aucune disponibilité ni note personnelle d’un membre réel de Pink Kulture / Magnolia ne doit être publiée dans ce dépôt.

## Fonctionnalités de la démo

- disponibilités par jour et par créneau ;
- statuts disponible, possible, indisponible ou non renseigné ;
- lecture individuelle et synthèse collective ;
- vues jour, semaine, mois et année ;
- repérage visuel des meilleurs créneaux communs ;
- gestion simulée des membres et paramètres ;
- interface mobile-first autonome ;
- stockage local de démonstration via `localStorage`, sans backend.

## Tester localement

Aucune installation n’est nécessaire.

1. Télécharger ou cloner le dépôt.
2. Ouvrir `index.html` dans un navigateur récent.

```bash
git clone https://github.com/GabeDurik/Pink_Hub_Team_Agenda.git
cd Pink_Hub_Team_Agenda
```

Puis ouvrir `index.html`.

## Statut technique historique

Il s’agit d’une **démonstration front-end** : les données, comptes, invitations, synchronisations et notifications ne sont pas reliés à un backend de production.

Toute reprise de ces fonctions doit désormais être évaluée dans le contexte de `LYRA_MapOS` plutôt que poursuivie ici comme produit concurrent.

## Auteur et écosystème

Conception : **Gabriel Bossuyt**  
Écosystème historique : **Pink Kulture / Pink Hub**  
Successeur fonctionnel : **LYRA_MapOS — module Agenda**

## Licence

Tous droits réservés. Voir le fichier `LICENCE`.
