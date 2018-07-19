

# Faisons des trucs sympa avec Arduino et Scratch !



## Objectifs

Le premier objectif de ce module est de s'initier à la robotique, à l'iade d'un Arduino.
Le second objectif est de prendre conscience de ses acquis en terme de code, via Scratch.



## Préparation

+ Installer [Arduino IDE](https://www.arduino.cc/) (sudo apt install arduino) et [S4A](http://s4a.cat)
+ Brancher l'arduino au PC, le capteur infrarouge et la diode selon les indications suivantes :
![infrared module wiring](d2bf7e68fbd325a5fd725721756472e2.jpg "Comment brancher le détecteur infrarouge ?")
![LED wiring](led-13-mega.png "Comment brancher la diode ?")

**Attention ! Celui qui crame le matos a un gage !**

+ Lancer s4a en USB
+ Créer un programme qui répond aux indications suivantes :
  + Si je passe ma main devant le capteur, on entend un bruit de cheval
  + A la troisième détection, ce n'est plus un bruit de cheval, mais un cri de personne !
  + La diode s'allume quand un bruit est généré
  + Après 3 détections, le programme s'arrête !


![Le projet](led-13-mega.png "Le projet")
