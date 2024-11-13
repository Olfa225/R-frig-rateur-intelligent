
Ce projet de "Smart Fridge" combine des technologies embarquées, de l'intelligence artificielle et du développement d'interface utilisateur pour créer un réfrigérateur intelligent capable de détecter et de surveiller son contenu, d'assurer la sécurité de l'accès et d'informer l'utilisateur en temps réel.

Fonctionnalités principales
1. Contrôle d'accès sécurisé
Module RFID et servo-moteur : Un système de contrôle d'accès par RFID est intégré pour sécuriser l'accès au réfrigérateur. Seul un badge RFID authentifié peut déverrouiller la porte, ce qui active un servo-moteur pour permettre l'ouverture.
2. Surveillance de la température et de l'humidité
Capteurs embarqués : Les capteurs intégrés mesurent en temps réel la température et l'humidité à l'intérieur du réfrigérateur.
Transmission des données : Ces informations sont envoyées à une interface graphique qui permet de surveiller les conditions de conservation des aliments à distance.
3. Détection des objets dans le réfrigérateur
Communication entre STM32 Nucleo et ESP32-CAM : Le microcontrôleur STM32 Nucleo communique avec un module ESP32-CAM pour capturer et analyser les images de l'intérieur du réfrigérateur.
Reconnaissance d'objets : Grâce à l'ESP32-CAM, le réfrigérateur peut détecter les objets présents, fournissant une vue d'ensemble du contenu en temps réel.
Aspects avancés du projet
1. Intelligence Artificielle (IA)
Reconnaissance des objets : Un modèle de vision par ordinateur est utilisé pour identifier automatiquement les articles présents dans le réfrigérateur, offrant ainsi à l'utilisateur des informations sur le stock d'ingrédients.
Amélioration continue : L'IA peut être améliorée pour identifier un plus large éventail d'objets et même suggérer des recettes en fonction du contenu.
2. Interface Utilisateur (UI)
Application Graphique : Une interface utilisateur conviviale affiche les données de température, d'humidité et le contenu du réfrigérateur.
Accessibilité : L'interface est conçue pour être intuitive, permettant un contrôle et une surveillance facile via un ordinateur ou un appareil mobile.

