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

Java 8 est connu pour ses Lambda,

mais il recèle des nouveautés pour le monde de l'embarqué,

et particulièrement pour l'internet des objets.

# Plan

* histoire
* Java SE
* Java Embeded
* Java ME
* L'avenir

# Back to the future

![oops](images/BackToTheFuture.jpg "Java ?") 

# Back to the future

![Star7](images/Star7.jpg "Java et Star7") 

# Back to the future

![Sérieux](images/BackToTheFuture.jpg "Soyons sérieux") 

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

# Java SE8

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

# Les plate-formes Java Embedded

![Java Embedded](images/JavaEmbedded.png "Java Embedded") 

# JSE Embedded

// TODO

# JME

RIP Nokia !

Symbian est &#x1f507; aphone

Java + SmartPhone = Android ?

# JME8

JME8 = IOT

Version Raspberry PI

Version Freescale FRDM-K64F

# Avantages Java ME8

+ alignement Java SE8/Java ME8
    - Stream
    - Lambda
    - Event/Listener
    - Les Enums
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

# Java Card

L'enfant pauvre, l'oublié

Assure la sécurité des Objets connectées

Possibilité de mettre des cartes a puces soudées dans les objets connectés

# Java dans le Cloud


# Conclusion
A quand une JVM sur Arduino
Quid de l'avenir ?
Java 9
