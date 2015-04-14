---
layout: master
title: Java8 IOT
---

# PresJava8IOT

## présentation des fonctionnalités Java8 pour l'internet des Objets

# Java 8 et l'IOT
Les nouveauté Java 8 pour l'Internet des Objets
						
Charles de MAGNEVAL

# présentation des fonctionnalités Java8 pour l'internet des Objets

Java 8 est connu pour ses Lambda, mais il recèle des nouveautés pour le monde de l'embarqué, et particulièrement pour l'internet des objets.

# Plan

* histoire
* Java SE
// * Java Embeded
* Java ME
* L'avenir

# Back to the future

![oops](http://i2.cdscdn.com/pdt2/3/0/8/1/700x700/auc5050293108308/rw/affiche-du-film-retour-vers-le.jpg "Java ?") 

# Back to the future

![Star7](http://assiste.com.free.fr/m/img/java_02.jpg "Java et Star7") 

# Back to the future

![Sérieux](http://i2.cdscdn.com/pdt2/3/0/8/1/700x700/auc5050293108308/rw/affiche-du-film-retour-vers-le.jpg "Soyons sérieux") 

* montre
* lunette
* voiture
* ...
et Java dans tous ça ?

# Les plate-formes Java

Jusqu'à Java 7
* Java Card pour la carte à puce
* Java ME (MidP, CLDC, CDC) pour le mobile
* Personnal Java pour le SmartPhone (hors Android et IOS) 
* Java SE pour le Desktop
* Java EE pour les serveurs

# Les plate-formes Java

Mais où sont les objets connectés ?
Sous Android ?

# Java Standard Edition

Pas adapté aux objets connectés
nécessite un OS, généralement une couche graphique.
Lourd (plusieurs Mo)

# Java SE8

pas encore Jigsaw
Mais l'instruction de la notion de profils, qui permet un sous découpage de la VM
Il existe 3 profils :
1 Version minimum
1 Version 1 + 
1 Version 2 + 

# Java SE8 Profile x

démo OSGI

// # JSE Embedded

// TODO

# JME

RIP Nokia !

Symbian est &#x1f507; aphone

Java + SmartPhone = Android

# JME8

JME8 = IOT
Version Raspberry PI
Version Freescale FRDM-K64F

# Avantages Java ME8

+ alignement Java SE8/Java ME8
    - Stream
    - Lambda
    - Event/Listener
+ Taille réduite :
    128 KB RAM 
    1 MB of Flash/ROM

# Avantages Java ME8

Gestion 
* des accès :
    + GPIOs
    + Analog to Digital Converter (ADC)
    + Digital to Analog Converter (DAC)
    + 
* des ports de communications :
    + SPI (MSIO)
    + I2C
    + UART
* Connectivité :
    + 3GPP (3rd Generation Partnership Project)
    + CDMA (Code division multiple access)
    + WiFi (Wireless Fidelity)


# Conclusion
A quand une JVM sur Arduino
Quid de l'avenir ?
Java 9
