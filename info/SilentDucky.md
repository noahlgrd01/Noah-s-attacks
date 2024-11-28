# But de l'attaque #
Le but de l’attaque est de pouvoir siphonner des fichiers spécifiques provenant d’un système GNU/Linux, à l’aide d’un Rubber Ducky (RD).

Voici une liste non exhaustive de répertoire qui pourrait être intéressant de syphoner :
- cd ~/.ssh
- cd ~/.gnupg
- nano ~/.bash_history
- nano /etc/resolv.conf
- nano /etc/crontab

# Clé USB #
Clé USB (Digispark (Attiny85), Teensy (Teensy 2.0 ou 3.2), Pro Micro (basé sur ATmega32u4), BadUSB (basé sur une clé USB avec firmware modifiable)).

La clé USB comportera un slot pour microSD

Le périphérique devra être nommé 'usb-rd'.

Pour compiler le fichier qui sera présent sur la microSD, il faut exécuter le fichier `compile.sh` dans SilentDucky/compile.sh. Un fichier `inject.bin` en ressortira.