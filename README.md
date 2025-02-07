# Visioconférence en Temps Réel

## Description du Projet

Le projet consiste à développer une plateforme de visioconférence en temps réel, permettant aux utilisateurs de se connecter et d'interagir via des flux vidéo, avec des fonctionnalités supplémentaires comme le chat textuel et la gestion des salles de discussion. L'objectif principal était de créer une application simple, robuste et fluide pour une expérience utilisateur optimale, même pour des utilisateurs peu expérimentés. Les défis incluent la gestion de la latence et des flux vidéo en temps réel.

## Outils et Technologies Utilisées

- **Frontend** : HTML, CSS (Bootstrap), JavaScript, Socket.IO (pour la communication en temps réel)
- **Backend** : Flask (serveur), Flask-SocketIO (gestion des websockets)
- **Compression Vidéo** : OpenCV (pour réduire la taille des frames vidéo en temps réel)

## Installation

### Prérequis

- Python 3.x
- Flask
- Flask-SocketIO
- OpenCV
- Socket.IO

### Installation des dépendances

```bash
pip install flask flask-socketio opencv-python
