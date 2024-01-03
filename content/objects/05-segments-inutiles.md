+++
showonlyimage = false
draft = false
image = "/objects/7c_001.jpg"
date = "2020-11-05T18:25:22+05:30"
title = "Les segments inutiles"
description = "Un millier de segments alors que 30 auraient suffit !"
weight = 0
+++

![](/objects/7c_001.jpg)


L'Objet est une horloge qui remet en perspective l'affichage du temps. La matrice, composée de 192 afficheurs 7 segments, affiche de manière cursive le temps qui passe. Absurdité de la chose puisque 4 de ces même afficheurs auraient suffi à donner l'heure.  

L'Objet a été conçu sur un principe de modularité puisque composé de 12 circuits comprenant chacun 16 afficheurs 7 segments. Ces circuit sont maintenus entre eux par un élégant châssis imprimé en 3D.   

![](/objects/7c_003.jpg)

 Il est architecturé autour d'une carte pilotant les 12 modules afficheurs. Celle-ci comprend une [**XIAO SAMD21**][2] de chez [**Seeed Studio**][1] et une RTC [**DS3231**][4] de chez [**Analog Devices**][3] 

Chaque carte afficheur embarque un [**TM1629A**][5] qui prend en charge le pilotage des 16 afficheurs 7 segments.  

[1]: https://www.seeedstudio.com/
[2]: https://wiki.seeedstudio.com/Seeeduino-XIAO/
[3]: https://www.analog.com/en/index.html
[4]: https://www.analog.com/en/products/ds3231.html
[5]: https://datasheet.lcsc.com/lcsc/1809042024_TM-Shenzhen-Titan-Micro-Elec-TM1629A_C19760.pdf


