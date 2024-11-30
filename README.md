# IOT Middleware

**IOT Middleware** est une plateforme basée sur **Dart** et **Flutter** qui permet de configurer et de gérer des communications VoIP en utilisant le protocole **SIP** avec des serveursn**Asterisk**. Le projet inclut une interface mobile pour enregistrer et gérer des agents utilisateur (User Agents) et permet des appels audio/vidéo entre eux.

## Fonctionnalités principales

- **Communication VoIP** : Intégration avec des serveurs SIP standard (Asterisk, FreeSWITCH, Kamailio, OpenSIPS).
- **Interface utilisateur mobile** : Gestion et enregistrement des agents utilisateur via une application Flutter.
- **Appels audio/vidéo** : Supporté par le plugin [flutter-webrtc](https://github.com/cloudwebrtc/flutter-webrtc).
- **Interopérabilité** : Compatible avec les plateformes iOS, Android, Web, macOS, Windows et Linux.

---

## Structure du projet

### 1. **SIP-UA**
Un module Dart pour implémenter les fonctionnalités SIP, portées depuis [JsSIP](https://github.com/versatica/JsSIP).  
Fonctionnalités :
- Support du protocole SIP sur WebSocket.
- Envoi de DTMF via RFC2833 ou INFO.
- Compatible avec des serveurs SIP standards comme Asterisk, Kamailio, et FreeSWITCH.

[Plus de détails sur Dart-SIP-UA](https://github.com/cloudwebrtc/dart-sip-ua).

---

### 2. **Asterisk**
Ce dossier contient les fichiers nécessaires pour configurer et déployer un serveur **Asterisk** dans un environnement Docker.  
Fonctionnalités :
- Configuration des extensions et agents utilisateur.
- Scripts pour déployer rapidement une infrastructure VoIP complète.

---

### Plateformes supportées

- [X] iOS
- [X] Android
- [X] Web
- [X] macOS
- [X] Windows
- [X] Linux

