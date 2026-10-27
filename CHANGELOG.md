# Changements

🇬🇧 [English version](CHANGELOG.en.md)

## Version 0.2.6-beta — Plus simple, plus économe

- **ajouter un appareil** commence par ce que tu ajoutes : **Lumière, Volets, Chauffage, Relais** ou **Divers** (tu
  écris toi-même ce que c'est, et ce nom devient celui de l'appareil) ; puis la marque ; Sally ne demande « Zigbee ou
  EnOcean ? » que si besoin (chez NodOn, la référence le dit : un 2 = EnOcean, un 4 = Zigbee) et lit à voix haute la
  bonne manipulation ;
- **économies automatiques** : une fenêtre ouverte plus de 30 secondes met le chauffage de la pièce en hors-gel, puis
  il reprend son mode à la fermeture ; une lumière oubliée dans une pièce vide depuis 30 minutes est éteinte ; l'accueil
  montre **ce que Sally t'a fait économiser ce mois-ci, en euros** (Réglages → Économies pour les couper) ;
- **routines** : nouvelle case **« Revenir comme avant à la fin »** (fenêtre refermée → chaque appareil reprend l'état
  qu'il avait) et nouvelle condition **« le chauffage n'est pas arrêté »** ;
- **tableau de bord** (Pièces → Tableau de bord) : une case par pièce, de la couleur de ce qui s'y passe ; tu peux y
  ajouter la **photo du plan de ta maison** et y poser chaque pièce ;
- **inviter la famille par QR code** : la personne le scanne avec son téléphone et se retrouve connectée, sans code à
  taper (une seule fois, pendant 24 heures) ;
- la tuile **« Je pars »** devient **« Je rentre »** quand tu es sorti ; **l'œil** pour voir ton code d'accès en le
  tapant ; **changer son prénom** ; **taille d'affichage « Petit »** au départ (Réglages pour changer) ;
- **volet EnOcean** : bouton **Stop**, et rappuyer sur la flèche du mouvement en cours l'arrête ;
- consignes d'appairage corrigées (module EnOcean : appui de plus de 5 secondes ; ampoule qui ne connaît pas la
  remise à zéro à distance) ; un appareil débranché qu'on retire de Sally quitte bien le réseau Zigbee.

## Version 0.2.5-beta — Sally 2.0 : la vie de famille

- **la vie de famille** : habitants (adultes et enfants), **messages** entre habitants livrés au bon moment (au lever,
  en passant dans une pièce…), **rappels**, **réveil sans sonnerie** (chauffage, lumière qui monte doucement, volets),
  **« bonne nuit »** qui dit ce qui reste ouvert, **veilleuse**, **résumé du matin** ;
- **« je pars » / « je rentre »** et **qui est là ?** ; quand l'alarme est armée, une minute pour rentrer avant l'alerte ;
- **liste de courses partagée**, avec une copie lisible sur le téléphone au magasin ;
- en vacances, Sally **rejoue les habitudes de la maison** ; date de retour : chauffage remis en confort avant ton arrivée ;
- **commande vocale dans les 5 langues**, sans Internet ; Sally **répond à voix haute** (voix de femme par défaut,
  au choix dans Réglages → Voix de Sally) ;
- **alertes dites à voix haute**, en carte sur l'accueil jusqu'à ce que tu les **effaces** ; « C'est l'interrupteur »
  pour une lampe coupée au mur ;
- **NodOn** : relais double, contact sec, mesure d'énergie, détecteur de mouvement et volet EnOcean ;
  **guide d'appairage par marque** dans l'assistant d'ajout ;
- corrections : clé Zigbee bloquée après une remise à zéro à distance, pourcentage de la lampe en direct,
  listes déroulantes lisibles.

## Version 0.2.4-beta — Sally 2.0 : code d'accès, achat et mises à jour (comprise dans la 0.2.5)

- **ta maison est protégée par un code d'accès** : sans lui, personne ne la pilote, même connecté à ton Wi-Fi. Tu le
  choisis au premier lancement (si tu avais une bêta 0.2, Sally te le demande à l'ouverture) ; chaque téléphone reste
  connecté ;
- **comptes pour la famille** et **accès invité** limité dans le temps, éventuellement à quelques pièces
  (Réglages → Comptes et accès) ;
- **code de secours** si tu oublies ton code d'accès ;
- **acheter Sally depuis l'application** (Réglages → Acheter Sally) : après le paiement, Sally s'active toute seule
  (la vente ouvrira prochainement ; pendant la bêta, la page d'achat permet de nous écrire avec ton code) ;
- **mises à jour** : si tu autorises Internet, Sally te prévient d'une nouvelle version (Réglages → Mises à jour) ;
  sur le Raspberry Pi, elle s'installe d'un bouton et revient seule à l'ancienne en cas de problème ;
- trois nouveaux sujets dans l'Aide : Code d'accès et comptes, Mises à jour, Acheter Sally.

## Version 0.2.3-beta — Sally parle ta langue

- **l'installateur demande ta langue** : français, anglais, allemand, espagnol ou italien (celle de Windows est
  proposée d'office) ;
- les raccourcis du menu Démarrer, le Lisez-moi et le message d'erreur (si Sally ne démarre pas) sont dans la
  langue choisie ;
- documentation en anglais sur GitHub.

## Version 0.2.2-beta — Bienvenue, et la sauvegarde réparée

- **assistant de bienvenue** au premier lancement : la langue, le nom de ta maison, puis les adresses pour ouvrir
  Sally sur ton téléphone ;
- **Réglages → Adresse de Sally** : les adresses à taper sur le téléphone, avec le nom en `.local` et l'adresse en
  chiffres (utile quand un antivirus bloque les adresses en `.local`) ;
- le **nom de ta maison** s'affiche en haut de l'accueil (modifiable dans Réglages → Ma maison) ;
- **correction importante** : restaurer une sauvegarde qui contient le réseau Zigbee échouait ; c'est réparé ;
- préparation du passage au Raspberry Pi : « Ma Sally Raspberry » dans Réglages retrouve un Raspberry Pi sur ton
  réseau et lui envoie ta maison (la version Raspberry Pi sera publiée prochainement) ;
- nouveau sujet dans l'Aide : « Passer au Raspberry Pi ».

## Version 0.2.1-beta — Sally parle, et un guide d'utilisation

- Sally parle pendant l'ajout d'un appareil (avec une voix installée sur l'ordinateur, sans Internet) ;
  un bouton permet de la faire taire ;
- elle demande dans quelle pièce mettre l'appareil : réponds à la voix (« le salon ») ou touche la pièce,
  maintenant affichée en boutons ; si la pièce n'existe pas encore (« la cuisine »), elle la crée ;
- quand la pièce est dite à la voix, Sally termine toute seule : elle ajoute l'appareil, ou lance l'essai et
  écoute ta réponse (« oui », « non, il descend », « rien ne se passe ») ;
- **interrupteurs et télécommandes** : Sally demande ce qu'ils doivent commander (« le volet du salon »), te fait
  appuyer sur la touche du haut puis du bas, et crée le lien toute seule ; bouton « Relier à un appareil » dans
  la fiche d'un interrupteur pour le changer plus tard ;
- **nouvel onglet Aide** : un guide d'utilisation complet, en 5 langues ;
- la reconnaissance de la voix écarte les réponses douteuses (bruit, écho).

## Version 0.2.0-beta — Sally entièrement refaite

Sally Home Connect a été reconstruite de zéro : plus simple, plus rapide, et toujours 100 % locale.

### Nouveautés

- nouveau tableau de bord, sur ordinateur et téléphone, avec cinq thèmes de couleurs ;
- pièces avec image, température, humidité et présence ;
- lumières, prises, volets roulants, chauffage (fil pilote et thermostats), capteurs ;
- routines « quand… si… alors… », ambiances, chauffage programmé à la semaine ;
- modes de la maison : présent, absent, nuit, vacances (avec présence simulée) ;
- énergie et coût, heures pleines et creuses ;
- alertes (fuite, fumée, pile faible, appareil qui ne répond plus) et journal de la maison ;
- assistant d'ajout d'appareils dans l'application ;
- sauvegarde et restauration en un fichier ;
- **commande vocale en français qui fonctionne sans Internet**, avec un micro sur chaque pièce ;
- **démonstration** : une maison et des appareils simulés, pour tout essayer sans matériel ;
- météo du jour, uniquement si tu l'autorises (éteinte par défaut) ;
- interface en 5 langues : français, anglais, espagnol, italien, allemand.

### Changements par rapport à la bêta 0.1

- Sally s'ouvre sur `https://localhost` (au lieu de `https://127.0.0.1:3443`) et sur `https://sally.local`
  depuis le téléphone ;
- plus besoin de Mosquitto ni de Python : tout est intégré ;
- Sally trouve toute seule les clés USB Zigbee et EnOcean ;
- l'essai gratuit dure désormais **30 jours** ;
- le mot de passe administrateur de la bêta 0.1 est retiré pour l'instant : des comptes pour la famille et un
  accès invité arrivent dans une prochaine version ;
- les appareils de la bêta 0.1 doivent être ajoutés à nouveau ;
- installateur plus léger (80 Mo au lieu de 147 Mo), raccourcis Démonstration et Arrêter dans le menu Démarrer.

### Limites connues

- toute personne connectée au Wi-Fi peut piloter la maison (en attendant les comptes) ;
- le certificat HTTPS est propre à Sally : le navigateur affiche un avertissement la première fois ;
- l'installateur n'est pas encore signé : Windows peut afficher un avertissement au téléchargement ;
- la commande vocale n'existe qu'en français pour l'instant.

## Version 0.1.2-beta — Multilingue

- interface et documentation en 5 langues.

## Version 0.1.1-beta — Création du mot de passe administrateur

- aucun mot de passe temporaire n’est fourni ;
- au premier accès à la Configuration, l’utilisateur crée son propre mot de passe ;
- confirmation visuelle lorsque les deux mots de passe sont identiques ;
- bouton pour afficher ou masquer le mot de passe ;
- le mot de passe est conservé localement dans le dossier de données de l’utilisateur.

## Version 0.1.0-beta — Bêta Windows

Première version bêta de Sally Home Connect pour Windows.

### Fonctionnalités

- installation Windows avec raccourci sur le Bureau ;
- essai gratuit de 60 jours ;
- gestion EnOcean et Zigbee ;
- commande vocale ;
- scénarios ;
- documentation intégrée ;
- accès administrateur protégé pour les pages de configuration ;
- licence d’essai de 60 jours.

### Sécurité et stockage

- programme installé dans `Program Files` ;
- données utilisateur séparées dans `AppData\Local` ;
- sauvegardes conservées lors des mises à jour ;
- code distribué sous forme obfusquée.

### Limites connues de la bêta

- la compatibilité dépend des modules EnOcean et Zigbee utilisés ;
- la configuration des ports série peut varier selon l’ordinateur ;
- le certificat HTTPS est local et peut générer un avertissement dans le navigateur ;
- des améliorations d’interface et de compatibilité sont prévues après les retours des testeurs.
