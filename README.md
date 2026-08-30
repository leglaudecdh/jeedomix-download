# Jeedomix

Jeedomix est une application Android permettant de piloter
vocalement une installation domotique Jeedom.

## Fonctionnalités

- Reconnaissance vocale.
- Pilotage des équipements Jeedom.
- Exécution d’interactions domotiques.
- Fonctionnement non-stop.
- Dialogue avec une intelligence artificielle, selon la configuration.

## Télécharger l’application

[Télécharger la dernière version de Jeedomix](https://github.com/leglaudecdh/jeedomix-download/releases/latest)

Dans la rubrique **Assets**, sélectionnez le fichier `.apk`.

## Installation

1. Téléchargez le fichier APK sur votre smartphone ou tablette Android.
2. Autorisez, si nécessaire, l’installation depuis cette source, du genre "Paramètres > Sécurité > Sources inconnues" etc.

   Remarque: 2 cas de figure (entre autres) chez moi:
   - Sur Samsung S4, il faut *Analyser l'application* puis approuver les autorisations (*). J'ai aussi dû m'y reprendre à 2 fois pour finaliser l'installation.
   - Sur S21, *Appli non sécurisée bloquée* => *Plus de détails* => *Installer quand même* :
   
   <img width="200" height="400" alt="image" src="https://github.com/user-attachments/assets/9f4a7e24-490a-43fb-87d3-9fe864e7eb99" />   <img width="200" height="400" alt="image" src="https://github.com/user-attachments/assets/56db99b9-11e2-4277-8a86-732db3b11f0f" />
   
   Donner les autorisations (*)
4. Installez l’application.
5. Renseignez les paramètres de votre installation Jeedom.

## Configuration nécessaire

- Adresse locale de votre installation Jeedom.
- Adresse publique, pour accès "world".
- Clé API Jeedom.
- Mot de déclenchement.
  
 <img width="216" height="468" alt="image" src="https://github.com/user-attachments/assets/c7803ea8-8876-4956-8411-2b93bcfa946c" />

 
## Compatibilité

Android 5.0 ou version ultérieure.

## Démonstration vidéo

Vidéo https://youtu.be/-NNZ8MlC6JA


## (*) Concernant les autorisations:
1. Audio: si pas de microphone, pas d'écoute...
2. Notification: pour avoir le retour de l'échange homme-machine ("chat")
3. Premier plan: idem, priorité d'affichage à la page d'accueil qui revient pour les échanges
4. Photos, fichiers musicaux,, etc. : uniquement pour machines obsolètes où un mp3 sert de feedback à la place d'une tonalité électronique (c'est le cas pour mon S4, et ce n'est pas indispensable)
