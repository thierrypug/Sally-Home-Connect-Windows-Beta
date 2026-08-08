# Installation de Sally Home Connect sous Windows

## Matériel nécessaire

Sally Home Connect pilote des équipements domotiques réels.

Selon votre installation, vous avez besoin de :

- **EnOcean** : un dongle USB EnOcean compatible, connecté à l’ordinateur ;
- **Zigbee** : une passerelle ou un dongle Zigbee compatible, configuré avec Zigbee2MQTT ;
- les modules domotiques correspondants : éclairages, volets, relais, chauffages, capteurs, etc.

Vous pouvez installer Sally sans matériel pour découvrir l’interface. En revanche, le pilotage réel des équipements nécessite le matériel adapté.

## Prérequis

- Windows 10 ou Windows 11 en 64 bits ;
- droits administrateur pour installer le programme ;
- un navigateur web récent.

Node.js est déjà inclus dans l’installateur : aucune installation supplémentaire n’est nécessaire.

## Télécharger Sally

1. Ouvrez l’onglet **Releases** du dépôt GitHub.
2. Téléchargez :

   ```text
   SallyHomeConnect-Setup-Beta-60j.exe
   ```

3. Une fois le téléchargement terminé, double-cliquez sur le fichier.

## Installer Sally

1. Acceptez la demande d’autorisation Windows.
2. Conservez le dossier proposé :

   ```text
   C:\Program Files\Sally Home Connect
   ```

3. Cochez l’option permettant de créer une icône sur le Bureau.
4. Terminez l’installation.

Sally Home Connect démarre automatiquement à la fin de l’installation.

## Premier démarrage

Sally s’ouvre dans votre navigateur à l’adresse :

```text
https://127.0.0.1:3443
```

Un avertissement peut apparaître car Sally utilise un certificat HTTPS local. Acceptez l’avertissement afin d’ouvrir l’application.

## Dossier des données

Vos données ne sont pas enregistrées dans le dossier du programme.

Elles se trouvent ici :

```text
C:\Users\VotreNom\AppData\Local\Sally Home Connect\data
```

Ce dossier contient notamment :

- la configuration du logement ;
- les pièces ;
- les équipements ;
- les scénarios ;
- les sauvegardes ;
- les associations EnOcean et Zigbee.

Ne supprimez pas ce dossier.

## Lancer Sally ultérieurement

Double-cliquez sur l’icône **Sally Home Connect** présente sur le Bureau.

L’application démarre sans fenêtre de terminal et ouvre automatiquement le navigateur.

## Désinstaller Sally

Utilisez les paramètres Windows :

```text
Paramètres > Applications > Applications installées > Sally Home Connect > Désinstaller
```

La désinstallation retire le programme, mais conserve vos données dans votre dossier utilisateur.

## Besoin d’aide

Consultez la documentation intégrée à Sally ou ouvrez une demande dans l’onglet **Issues** du dépôt GitHub.