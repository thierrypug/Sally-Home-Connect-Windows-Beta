# Sally Home Connect — bêta Windows

**Ta maison connectée, sans travaux, et tes données restent chez toi.**

Sally Home Connect pilote tes lumières, prises, volets et chauffage depuis ton ordinateur et ton téléphone,
**100 % en local** : pas de compte, pas de cloud, aucune donnée de ta maison ne sort de chez toi.

> **Nous cherchons des testeurs !** Essaie Sally et dis-nous ce que tu en penses :
> onglet [Issues](../../issues) ou **sallyhomeconnect@gmail.com**

## Télécharger

👉 [**Télécharger la dernière version**](../../releases/latest) : fichier `SallyHomeConnect-Setup-Beta-v….exe`

- Windows 10 ou 11, 64 bits
- **30 jours d'essai gratuit**, avec toutes les fonctions
- Rien d'autre à installer : Node.js est inclus
- **Pas de matériel ? Une démonstration** avec une maison et des appareils simulés est incluse

Le guide pas à pas : [INSTALLATION-WINDOWS.md](INSTALLATION-WINDOWS.md)

## Ce que Sally sait faire

- Tableau de bord simple, sur ordinateur et téléphone
- Lumières, prises, volets roulants, chauffage (fil pilote et thermostats), capteurs
- Routines (« quand… si… alors… »), ambiances, chauffage programmé à la semaine
- Modes de la maison : présent, absent, nuit, vacances (avec présence simulée)
- Suivi de l'énergie et de son coût (heures pleines et creuses)
- Alertes : fuite d'eau, fumée, pile faible, appareil qui ne répond plus
- **Commande vocale en français, qui fonctionne sans Internet** : la voix ne quitte jamais la maison
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
- Sally ne consulte jamais Internet sans ton accord. Seule la météo peut l'être, si tu l'autorises dans les Réglages.

## Bon à savoir pour cette bêta

- Toute personne connectée à ton Wi-Fi peut piloter la maison : les comptes et l'accès invité arrivent bientôt.
- La version finale de Sally est prévue pour un **Raspberry Pi**, allumé jour et nuit sans écran. Elle n'est pas
  encore publiée : ta maison créée pendant l'essai pourra y être transférée sans rien refaire.
- La bêta est **gratuite** et fournie **telle quelle, sans garantie** : c'est une version d'essai, des défauts
  peuvent subsister. Elle ne collecte aucune donnée : tout reste sur ton ordinateur.
- Les nouveautés de chaque version : [CHANGELOG.md](CHANGELOG.md)

## Donner ton avis

Ce qui marche, ce qui bloque, ce qui manque, ton matériel… tout nous intéresse :
onglet [Issues](../../issues) ou **sallyhomeconnect@gmail.com**

## Droits

Sally Home Connect est un logiciel protégé par le droit d'auteur. Cette bêta est prêtée pour essai :
il est interdit de la modifier, de la copier ou de la redistribuer sans l'accord de son auteur.
