# projet_4-linux
pré-requis :   
Il faut tout d'abord prendre en main le sense hat.  
Le sense hat permet de récupérer toute les informations que l'on veut transmettre.  
Il faut installer mosquitto, qui nous permettra de faire la communication.  
Il faut de plus sur node red, installer les palettes en liens avec sense-hat et créer le dashboard.  

Node-red:   
Ci-joint le fichier json, cependant l'adresse IP de ma raspberry change car je connecte celui-ci en wifi avec mon téléphone.
Donc les adresses IP inscrites sur le node MQTT out change.  

Pour la RP1:   
Nous ne pouvions pas envoyer les informations MOTION et ENVIRONNEMENT en même temps.  
Donc la RP1 recoit les informations d'ENVIRONMENT SENSORS et envoit les informations de MOTIONS SENSORS.  
Le message 'textBox' est aussi envoyé de la RP1 vers la RP2.  
