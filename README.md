# Jeedomix

Jeedomix est une application Android permettant de piloter
vocalement une installation domotique Jeedom.



# Motivation

J'ai toujours aimé les histoires où l'individu parle à sa maison et la gère. L'arrivée des Google Home en combinaison avec le merveilleux outil 'interactions' de Jeedom (dont personnellement, je ne trouve le plein potentiel qu'avec des requêtes vocales) m'a permis de concrétiser ce rêve d'enfant. Mais très vite cette façon d'apostropher l'enceinte par "ok google" puis de prononcer la demande puis d'attendre parfois plus de 5 secondes sa réalisation... m'a lassé. Je me suis fixé comme objectif de recoller à un comportement plus proche de la réalité. On ne demande pas à un assistant: ok Sébastien donne-moi la clé de 12. On se contente de Sébastien, (donne-moi) la clé de 12 :-)

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
- Mot de déclenchement (au choix, discriminant au possible. Eviter 'Donald' quand la télévision livre les infos :-)
  
 <img width="216" height="468" alt="image" src="https://github.com/user-attachments/assets/c7803ea8-8876-4956-8411-2b93bcfa946c" />

## Déroulement basique et obligations syntaxiques

 ***Côté Jeedomix*** et partie jeedom:
 
***Mot d'appel => ordre vocal =>*** Interactions côté Jeedom => Réponse de Jeedom (soit exécution de l'ordre et ***feedback sur l'app***, soit échec car cas non prévu dans les interactions et ***"je ne comprends pas" sur l'app***)

Exemple, si l'équipement télé est géré par les interactions: 

<img width="400" height="350" alt="image" src="https://github.com/user-attachments/assets/797fc522-586a-46af-b5c3-c0c61af8be26" />

Jarvis, allume la télé                |          Feedback: Equipement coin télé activé.

<img width="280" height="210" alt="image" src="https://github.com/user-attachments/assets/ccc99fce-4a77-47b2-a0c6-50d257ada1ca" />




 
## Compatibilité

Android 5.0 ou version ultérieure.

## Démonstrations vidéo

1) Démos sur 4 machines: https://youtu.be/-NNZ8MlC6JA
2) Comparaison latences Google Home-Jeedomix:https://youtu.be/Bjnyc0yIi30
3) Mon petit bonus perso (IA): https://youtu.be/5AFxjV6Et_U


## (*) Concernant les autorisations:
1. Audio: si pas de microphone, pas d'écoute...
2. Notification: pour avoir le retour de l'échange homme-machine ("chat")
3. Premier plan: idem, priorité d'affichage à la page d'accueil qui revient pour les échanges
4. Photos, fichiers musicaux,, etc. : uniquement pour machines obsolètes où un mp3 sert de feedback à la place d'une tonalité électronique (c'est le cas pour mon S4, et ce n'est pas indispensable)
