# Sally Home Connect — bêta Windows

🇬🇧 [English version](README.en.md)

**Ta maison connectée, sans travaux, et tes données restent chez toi.**

Sally Home Connect pilote tes lumières, prises, volets et chauffage depuis ton ordinateur et ton téléphone,
**100 % en local** : pas de compte en ligne, pas de cloud, aucune donnée de ta maison ne sort de chez toi.

> **Nous cherchons des testeurs !** Essaie Sally et dis-nous ce que tu en penses :
> onglet [Issues](../../issues) ou **sallyhomeconnect@gmail.com**

## Télécharger

👉 [**Télécharger la dernière version**](../../releases/latest) : fichier `SallyHomeConnect-Setup-Beta-v….exe`

- Windows 10 ou 11, 64 bits
- **30 jours d'essai gratuit**, avec toutes les fonctions
- Rien d'autre à installer : Node.js est inclus
- Installateur en français, anglais, allemand, espagnol et italien
- **Pas de matériel ? Une démonstration** avec une maison et des appareils simulés est incluse

Le guide pas à pas : [INSTALLATION-WINDOWS.md](INSTALLATION-WINDOWS.md)

## Ce que Sally sait faire

- Tableau de bord simple, sur ordinateur et téléphone
- Lumières, prises, volets roulants, chauffage (fil pilote et thermostats), capteurs
- Routines (« quand… si… alors… »), ambiances, chauffage programmé à la semaine
- Modes de la maison : présent, absent, nuit, vacances (avec présence simulée)
- Suivi de l'énergie et de son coût (heures pleines et creuses)
- Alertes dites à voix haute : fuite d'eau, fumée, pile faible, appareil qui ne répond plus
- **Code d'accès** et comptes pour la famille, accès invité limité dans le temps
- **Commande vocale dans les 5 langues, qui fonctionne sans Internet** : la voix ne quitte jamais la maison ; Sally te répond à voix haute
- **La vie de famille** : messages entre habitants, rappels, réveil sans sonnerie, « bonne nuit », « je pars / je rentre », liste de courses partagée
- **Sally te fait économiser** : chauffage coupé quand une fenêtre reste ouverte, lumières oubliées éteintes, bilan du mois en euros
- Tableau de bord des pièces (avec le plan de ta maison si tu veux), invitation de la famille par QR code
- Interface en français, anglais, espagnol, italien et allemand

## Matériel compatible

Sally trouve toute seule la clé USB branchée sur l'ordinateur :

| Technologie | Clés reconnues |
|---|---|
| Zigbee | Sonoff ZBDongle-P, Sonoff ZBDongle-E, ConBee II |
| EnOcean | EnOcean USB 300 |

Plusieurs milliers d'appareils Zigbee sont reconnus (Philips Hue, IKEA, Aqara, Sonoff, NodOn, Legrand…),
grâce à une bibliothèque fournie avec Sally : aucune recherche sur Internet.

## Une domotique vraiment locale

- Aucun compte en ligne, aucun abonnement, aucun service cloud.
- Tout fonctionne sans Internet.
- Sally ne consulte jamais Internet sans ton accord. Seules la météo et la recherche de mises à jour peuvent l'être, si tu l'autorises dans les Réglages.

## Bon à savoir pour cette bêta

- Ta maison est protégée par un code d'accès, choisi au premier démarrage : personne ne la pilote sans lui,
  même connecté à ton Wi-Fi.
- La version pour vivre avec Sally tourne sur un **Raspberry Pi**, allumé jour et nuit sans écran :
  [**Sally Home Connect – Raspberry Pi**](https://github.com/thierrypug/Sally-Home-Connect-Raspberry-Pi). Ta maison
  créée pendant l'essai y passe en un bouton, sans rien refaire.
- La bêta est **gratuite** et fournie **telle quelle, sans garantie** : c'est une version d'essai, des défauts
  peuvent subsister. Elle ne collecte aucune donnée : tout reste sur ton ordinateur.
- Les nouveautés de chaque version : [CHANGELOG.md](CHANGELOG.md)

## Donner ton avis

Ce qui marche, ce qui bloque, ce qui manque, ton matériel… tout nous intéresse :
onglet [Issues](../../issues) ou **sallyhomeconnect@gmail.com**

## Droits

Sally Home Connect est un logiciel protégé par le droit d'auteur. Cette bêta est prêtée pour essai :
il est interdit de la modifier, de la copier ou de la redistribuer sans l'accord de son auteur.
