# COMMANDER-UNE-AMPOULE-AVEC-UNE-TELECOMMANDE-ET-ARDUINO
l'objectif est de commander une lampe 220V avec une télécommande et une carte arduino

*****  1ere étape

extraire et installer la librairie Arduino-IRremote-master dans le dossier d'installation. le mien est 
C:\ Program Files (x86)\ arduino \ libraries

*****  2ème étape

Faire le schéma de câblage en respectant les connection. vous pouvez ne pas mettre le out du récepteur infrarouhge au A0 et le mettre sur un autre pin mais veuillez a changer cela dans le code

****   3ème étape

charger le code de réception sur la carte arduino et lire dans le moniteur série les valeurs hexadécimal reçu lorsqu'on appuie sur chaque boutton

****   4ème étape

charger et modifier l'un des codes de réception en fonction de l'utilisation que vous voulez en faire
allumer et éteindre sur deux bouttons différens ou allumer et éteindre sur le même boutton. vous pouvez changer les valeurs hexadecimal présentent dans mon code si vous souhaitez utiliser d'autres boutons que les miens.

