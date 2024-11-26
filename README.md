# But de l'attaque #
Le but de l’attaque est de pouvoir siphonner des fichiers spécifiques provenant d’un système GNU/Linux, à l’aide d’un Rubber Ducky (RD).

Les fichiers et répertoires cibles sont

- cd ~/.ssh
- cd ~/.gnupg
- nano ~/.bash_history
- nano /etc/resolv.conf
- nano /etc/crontab

# Clé USB #
Clé USB (Digispark (Attiny85), Teensy (Teensy 2.0 ou 3.2), Pro Micro (basé sur ATmega32u4), BadUSB (basé sur une clé USB avec firmware modifiable)).

Le périphérique devra être nommé 'usb-rd'

Le fichier `payload.txt` doit être compilé pour être compris par le RD.
`java -jar DuckEncoder.jar -i payload.txt -o inject.bin`