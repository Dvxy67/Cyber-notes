# La sécurité offensive : penser comme un attaquant

**Parcours :** Cyber Security 101 — Start Your Cyber Security Journey
**Date :** 2026-11-11

## Le concept en mes mots
J'ai vu la différence entre l'attaque (sécurité offensive) et la défense (sécurité défensive).

L'attaque va chercher des failles en fouillant partout. La défense, elle, ne fouille pas : elle essaie de sécuriser au maximum le site web avec plusieurs couches de protection et des alertes en cas d'intrusion. Elle surveille aussi les logs pour repérer une activité inhabituelle.

_À compléter : pourquoi une entreprise ferait-elle attaquer ses propres systèmes ?_

En pratique, j'ai cherché des fichiers et des pages cachés sur un site web pour trouver une faille, et j'ai réussi à l'exploiter.

## Schéma / capture
(lien vers une image dans /assets si utile)

## Commandes et outils
| Commande | Ce qu'elle fait |
|----------|-----------------|
| `dirb <url>` | Trouve les fichiers et pages cachés d'un site web. |

dirb utilise une liste des mots les plus souvent utilisés pour nommer des pages. Il envoie une requête au serveur pour chaque mot, l'un après l'autre : c'est de cette façon qu'il trouve des pages.

## Ce qui m'a posé problème
Pour l'instant, c'était simple : rien ne m'a posé problème.

## Pour aller plus loin
- [Room TryHackMe : Offensive Security Intro](https://tryhackme.com/room/offensivesecurityintro)
