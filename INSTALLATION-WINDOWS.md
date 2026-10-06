# Installation de Sally Home Connect sous Windows

🇬🇧 [English version](INSTALLATION-WINDOWS.en.md)

## Ce qu'il faut

- Windows 10 ou Windows 11, 64 bits ;
- les droits administrateur pour installer le programme ;
- un navigateur récent (Edge, Chrome, Firefox).

Node.js est inclus dans l'installateur : rien d'autre à installer.

**Pour piloter de vrais appareils**, il faut aussi une clé USB branchée sur l'ordinateur :

| Technologie | Clés reconnues |
|---|---|
| Zigbee | Sonoff ZBDongle-P, Sonoff ZBDongle-E, ConBee II |
| EnOcean | EnOcean USB 300 |

**Sans matériel**, tu peux tout découvrir avec la démonstration (maison et appareils simulés).

## Télécharger

1. Ouvre l'onglet **Releases** du dépôt GitHub.
2. Télécharge le fichier de la dernière version, par exemple :

   ```text
   SallyHomeConnect-Setup-Beta-v0.2.3-beta.exe
   ```

3. Double-clique sur le fichier téléchargé.

Windows peut afficher « Windows a protégé votre ordinateur » : l'installateur n'est pas encore signé.
Clique sur **Informations complémentaires** puis **Exécuter quand même**.

## Installer

1. Accepte la demande d'autorisation de Windows.
2. Choisis la langue de l'installateur (celle de Windows est proposée d'office).
3. Garde le dossier proposé (`C:\Program Files\Sally Home Connect`).
4. Laisse cochée l'icône sur le Bureau. Coche « Démarrer Sally avec Windows » si tu veux qu'elle se lance
   à chaque démarrage de l'ordinateur.
5. Termine l'installation : Sally démarre et ton navigateur s'ouvre.

**Tu avais une bêta 0.1 ?** Installe simplement par-dessus : l'ancienne version est remplacée.
Tes appareils devront être ajoutés à nouveau, car Sally a été entièrement refaite (voir le CHANGELOG).

## Premier démarrage

Le navigateur s'ouvre sur :

```text
https://localhost
```

Il affiche un avertissement de sécurité : c'est normal, Sally utilise son propre certificat, créé sur ton
ordinateur. Clique sur **Paramètres avancés** puis **Continuer vers localhost**.

Branche ta clé USB **avant** de démarrer Sally : elle la trouve toute seule. Ajoute ensuite tes appareils
avec le bouton **Ajouter un appareil**.

## Les raccourcis

Dans le menu Démarrer, dossier **Sally Home Connect** :

- **Sally Home Connect** : ta maison (aussi sur le Bureau) ;
- **Sally Home Connect - Démonstration** : la maison simulée, sur `https://localhost:3443` ;
- **Arrêter Sally Home Connect** : arrête Sally et la démonstration ;
- **Lisez-moi** et **Désinstaller**.

Sally tourne sans fenêtre. Cliquer de nouveau sur le raccourci rouvre simplement le navigateur.

## Sur le téléphone

Connecte le téléphone au même Wi-Fi que l'ordinateur et ouvre :

```text
https://sally.local
```

Accepte l'avertissement de sécurité comme sur l'ordinateur. Tu peux ensuite ajouter Sally à l'écran
d'accueil du téléphone (menu du navigateur → « Ajouter à l'écran d'accueil »).

## Où sont mes données ?

Pas dans le dossier du programme, mais ici :

```text
C:\Users\TonNom\AppData\Local\Sally Home Connect
```

On y trouve la maison (pièces, appareils), les routines, les réglages, les sauvegardes, le réseau Zigbee
et les journaux (`logs`). La désinstallation garde ce dossier.

## Si Sally ne démarre pas

- Un message s'affiche avec l'emplacement du journal : `AppData\Local\Sally Home Connect\logs\sally.log`.
- Envoie-nous ce fichier par l'onglet **Issues** ou à **sallyhomeconnect@gmail.com**.

## Désinstaller

```text
Paramètres > Applications > Applications installées > Sally Home Connect > Désinstaller
```

Le programme est retiré ; tes données restent dans ton dossier utilisateur.
