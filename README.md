# 🐱 Distributeur Automatique de Nourriture pour Animaux avec RFID 🐾

Ce projet consiste en la conception et la réalisation d'un distributeur automatique de nourriture pour animaux basé sur la technologie RFID. Un tag RFID est utilisé pour identifier l'animal autorisé à accéder à la nourriture. Lorsqu'un tag valide est détecté, un servomoteur s'active pour distribuer la nourriture, et un écran LCD affiche les informations en temps réel.

## 🛠 Matériels Utilisés:
- **Carte Arduino Uno**
-  **Module RFID RC522**
-  **Afficheur LCD 16x2 avec interface I2C**
-  **Servomoteur SG90**
-  **Alimentation 5V**
-  Divers composants électroniques (câbles, résistances, etc.)

## 🎨 Schéma de Câblage:
Un schéma de connexion a été réalisé pour organiser les différents composants. Voici les connexions principales :
- **Module RFID RC522** : Connecté à l'Arduino via SPI.
- **Servomoteur** : Connecté à la broche **9** de l'Arduino.
- **LCD I2C** : Connecté aux broches **SDA/SCL** de l'Arduino.
- **Alimentation** : Arduino alimenté en **5V**.
  ![image](https://github.com/user-attachments/assets/c70628ac-6950-47de-81e2-d63bc639934b)


## 🔧 Installation et Utilisation
1. 💻 **Programmation avec Arduino IDE**
   - Installer la bibliothèque **MFRC522** pour le module RFID.
   - Installer la bibliothèque **LiquidCrystal_I2C** pour l'affichage LCD.
   - Téléverser le code sur l'Arduino Uno.

2.  **Fonctionnement**
   - Approcher un tag RFID autorisé.
   - L'écran LCD affiche l'état du système.
   - Si le tag est reconnu, le servomoteur distribue la nourriture.
   - Si le tag est inconnu, l'accès est refusé.

##  Photo du distributeur:
![image](https://github.com/user-attachments/assets/2401874f-2242-465a-ab79-0d3596cc427a)
![image](https://github.com/user-attachments/assets/abd24df4-b433-498e-9501-0384079c08fa)



