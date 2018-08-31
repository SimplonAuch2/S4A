

# Faisons des trucs sympa avec Arduino et Scratch !



## Objectifs

1. Le premier objectif de ce module est de s'initier à la robotique, à l'aide d'un Arduino UNO.
2. Le second objectif est de prendre conscience de ses acquis en terme de code, via Scratch.



## Préparation

+ Installer [Arduino IDE](https://www.arduino.cc/) (sudo apt install arduino) et [S4A](http://s4a.cat)
+ Connecter le capteur infrarouge et la diode selon les schémas suivants :
![infrared module wiring](https://github.com/SimplonAuch2/S4A/blob/master/infrared.resized.jpg "Comment brancher le détecteur infrarouge ?")
![LED wiring](../blob/master/assetsled.resized.png "Comment brancher la diode ?")

**Attention ! Celui qui crame le matos a un gage !**

+ Brancher l'arduino au PC en USB, puis Lancer s4a.
+ Créer un programme qui répond aux indications suivantes :
  + Si je passe ma main devant le capteur, on entend un bruit de cheval
  + A la troisième détection, ce n'est plus un bruit de cheval, mais un cri de personne !
  + La diode s'allume quand un bruit est généré, et s'éteind quand le son est terminé.
  + Après 3 détections, le programme s'arrête !


![Le projet](../blob/master/assets/IMG_20180719_123834.resized.jpg "Le projet")
