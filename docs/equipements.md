---
layout: default
title: Équipements et instrumentation
nav_order: 3
---

# Équipements et instrumentation

Cette page présente les éléments imaginés pour illustrer la ligne. Un équipement réalise une action mécanique ou un transfert ; un capteur fournit une information ; un actionneur agit sur le procédé.

## Inventaire fonctionnel

| Poste | Équipement illustratif | Capteur possible | Actionneur possible |
|---|---|---|---|
| Dosage | Réservoir et doseur | Détection de niveau | Pompe de transfert |
| Mélange | Cuve et agitateur | Détection de niveau | Moteur d'agitation |
| Moulage | Trémie et doseuse | Détection de présence du moule | Vérin ou vanne simulée |
| Refroidissement | Convoyeur et zone d'attente | Détection de présence | Motoréducteur |
| Conditionnement | Compteur et poste de sachet | Cellule de comptage | Convoyeur et système de fermeture simulé |

## Différence entre capteur et actionneur

- Un **capteur** observe une grandeur ou un état : présence, position, niveau, température simulée.
- Un **actionneur** reçoit une commande et agit : moteur, pompe, vérin, vanne ou voyant.

## Fiches équipement à compléter

Pour documenter chaque élément, conserver la même fiche :

| Information | Exemple de contenu |
|---|---|
| Identifiant | CAP-01 |
| Désignation | Détecteur de présence |
| Fonction | Signaler qu'un moule est en position |
| Type de signal | TOR (tout ou rien) |
| Emplacement | Poste de moulage |
| État normal | À définir |
| Test associé | Vérifier le changement d'état à la détection |

## Règles de nommage proposées

- `CAP-` : capteur.
- `ACT-` : actionneur.
- `MOT-` : moteur.
- `POSTE-` : poste de production.

{: .warning }
> Cet inventaire est une proposition pédagogique. Il ne décrit pas une machine réelle et ne doit pas être utilisé pour piloter un équipement physique.
