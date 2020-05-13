La maxi liste des ressources pour faire (un bon) robot à Eurobot
===============

Ce repo est destiné à compiler et partager les ressources (cours/vidéos/composants/discussions/liens) en lien avec la compétition [Eurobot](https://www.eurobot.org/).

Les cours, en PDF de préférence, sont sauvegardés sur le repo afin d'assure leur longévité (même si ça reste à prouver).

Si un document vous appartient et que vous souhaitez le faire retirer, merci de nous contact.

Vous pouvez contribuer en créant une [Pull Request](https://github.com/VRAC-team/ressources/pulls)


---------------
# 1. Ressources académiques

## 1.1 Pour bien commencer

**RCVA: Réflexions sur un robot Eurobot en 9 chapitres**

> 1. Rappels cinématiques et définition du coefficient d’adhérence
> 2. Etude du phénomène de glissement en phase accélération
> 3. Choix d’un profil de vitesse
> 4. Les lois mécaniques et thermiques dans un moteur
> 5. Condition de glissement en cas de blocage du robot
> 6. Choix de la vitesse et de l’accélération
> 7. Essais avec enregistrements
> 8. Asservissement
> 9. Quelques questions réponses
> 
> [**PDF - RCVA - Réflexions sur un robot Eurobot**](http://www.rcva.fr/wp-content/uploads/2016/12/devoir_de_vacances.pdf)

**Cubot: Asservissement polaire en 6 chapitres**

> 1. Cas de charge
> 2. Odométrie
> 3. Calibration de l'odométrie
> 4. Calcul de la consigne
> 5. Calcul des rampes de vitesse
> 6. PID
> 7. Synthèse
> 
> [**PDF - Atelier asservissement polaire**](asservissement/Cubot-atelier_asservissement.pdf)
> 
> [**EXCEL - Simulation asservissement polaire**](asservissement/Cubot-asservissement.xlsx)
> 
> [EXCEL - Génération de profile trapézoidal de vitesse](asservissement/Cubot-profil_de_vitesse.xlsx)

[**Les dix commandements version OMyBot**](https://twitter.com/TeamOmybot/status/1128554678101467136)

## 1.2 Base roulante

### 1.2.1 Odométrie

[WEB - CVRA - Odometry calibration](https://cvra.ch/robot-software/howto/calibrate-odometry/)

[VIDEO - Robotic-System - Calibrage de l'odométrie](https://www.youtube.com/watch?v=X5PMFvVecXU)

[PDF - RCVA - Odométrie avec correction centrifuge](odometrie/RCVA-odometrie.pdf)

[PDF - RCVA - Trajectoires courbes et odométrie, De l’importance de la différence de diamètre des deux roues
codeuses](odometrie/RCVA-Conseils_theoriques_pour_Eurobot.pdf)

[VIDEO - RCVA - comparaison approximation linéaire/circulaire, correction centrifuge](https://www.youtube.com/watch?v=KQzfMAJyvB0)

[VIDEO - RCVA - odométrie](https://www.youtube.com/watch?v=557l7JOs35E)

[PDF - High-Precision Robot Odometry Using an Array of Optical Mice](https://pdfs.semanticscholar.org/37ca/1fc2dcc4c0cf860fc0b00542fc7cb59c579f.pdf)

### 1.2.2 Roues

[**WEB - Erich Styger - Making Perfect Sticky DIY Sumo Robot Tires**](https://mcuoneclipse.com/2017/12/28/making-perfect-sticky-diy-sumo-robot-tires/)

[FORUM - Robotech Legends - Moulage de pneus en polyuréthane](https://www.planete-sciences.org/forums/viewtopic.php?t=18632)

[VIDEO - Barbatronic - Moulage de pneus en silicone](https://www.youtube.com/watch?v=EGPVa1ZnXe8)

[VIDEO - Micro Technology - test d'adhérence des roues](https://www.youtube.com/watch?v=cPfP7zyS0kU)

### 1.2.3 Moteurs

[PDF - ANCR - Dimensionner ses moteurs](moteurs/ANCR-Dimensionner_ses_moteurs.pdf)

[PDF - TechTheTroll - Dimensionnement des moteurs de propulsion](https://techthetroll.files.wordpress.com/2016/06/techthetroll-dimensionnement-des-moteurs-de-propulsion.pdf)

[VIDEO - Robert Cowan - Montage de réducteur planétaire sur un moteur brushless](https://www.youtube.com/watch?v=TfYZbjtgO0k)

## 1.3 Asservissement

[PDF - totofweb - Le PID utilisé en régulation de position et/ou de vitesse de moteurs électriques](asservissement/totofweb-PID_régulation_de_position_vitesse.pdf)

[PDF - Microb Technology - Documentation de l'asservissement, librairie Aversive, évitement](asservissement/MicrobTechnology-wiki_asservissement_lib_aversive.pdf)

[PDF - RCVA - Asservissement du robot à une trajectoire](http://www.rcva.fr/wp-content/uploads/2016/12/asservissement.pdf)

[PDF - RCVA - Montée de tremplin par le robot RCVA sans terme intégral](http://www.rcva.fr/wp-content/uploads/2016/12/Montee_De_Tremplin_Sans_Terme_Integral_RCVA.pdf)

[VIDEO - RCVA - Asservissement en rotation avec un gyromètre ADXRS453](https://www.youtube.com/watch?v=p0cm7LnMXOc)

[VIDEO - RCVA - cours asservissement polaire](https://www.youtube.com/watch?v=JYZ_2y8k1Os)

[PDF - TechTheTroll - Les trajectoires courbes dans la bonne humeur: de l’asservissement à la planification](https://techthetroll.files.wordpress.com/2016/07/trajectoire_courbe.pdf)

[PDF - Rich LeGrand - Closed-Loop Motion Control for Mobile Robotics](https://www.cs.hmc.edu/~dodds/projects/RobS05/XPort/XPortArticle.pdf): un Game Boy Advance, des roues holonomes, des legos

### 1.3.1 Planificateur de trajectoire

[LIBRARIE - The Kraken Pathfinding - A tentacle-based pathfinding library for nonholonomic robotic vehicles](https://github.com/kraken-robotics/The-Kraken-Pathfinding)

## 1.4 Balises

[PDF - totofweb - Balise infrarouge](balise/totofweb-balises_IR.pdf)

[WEB - Barbatronic - Reflective lidar for robotic and the eurobot competition](http://fabacademy.org/2019/labs/lamachinerie/students/adrien-bracq/projects/final-project/)

[PDF - CVRA - Development of an ultra-wide band indoor positioning system](https://github.com/cvra/robot-software/blob/1d208d0d5882d5526eef758eae61f5626291a016/uwb-beacon-firmware/doc/report.pdf)

[PDF - Microb Technology - Faire des balises laser en buvant des bières](balise/MicrobTechnology-Faire_des_balises_laser_en_buvant_des_bieres.pdf)

[VIDEO - ESEO - localisation par balises infrarouges](https://www.youtube.com/watch?v=bGoXEwQ0UQs)

## 1.5 Simulation

[VIDEO - ESEO - simulateur de match](https://www.youtube.com/watch?v=fo-87AF2Fr4), [article sur leur site](https://robot-eseo.fr/strategie-du-robot-sur-simulateur/)

## 1.6 Communication sans-fil

[FORUM - Pourquoi éviter le WiFi 2.4GHz](https://www.planete-sciences.org/forums/viewtopic.php?f=97&t=16969)


---------------
# 2. Composants, fabricants, sites marchands

## 2.1 Cartes de développement et IDE

[STM32](https://www.st.com/en/evaluation-tools/stm32-mcu-mpu-eval-tools.html)

> outils:
> * [LL, HAL, CMSIS](https://www.st.com/en/embedded-software/stm32cube-mcu-mpu-packages.html#products)
> * [Mbed OS](https://os.mbed.com/code/): open-source operating system for platforms using Arm microcontrollers
> * [libopencm3](https://github.com/libopencm3/libopencm3): open-source firmware library for various ARM Cortex-M microcontrollers
> * [ChibiOS](https://github.com/ChibiOS/ChibiOS): complete development environment for embedded applications including RTOS, an HAL, peripheral drivers, support files and tools.

> IDE:
> * [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html): Combinaison de l'IDE TrueSTUDIO avec STM32CubeMX
> * [System Workbench for STM32](https://www.st.com/en/development-tools/sw4stm32.html): Supporte mbed (nécéssite une [manip pour corriger quelques erreurs](ide/fix_mbed_import_sw4stm32.txt))
> * [Mbed online compiler](https://os.mbed.com/): IDE en ligne, pas de débogueur, intègre un gestionnaire de version. Attention cependant à avoir une solution de secour lors de la coupe au cas où il serait en maintenance quelques heures
> * [Mbed Studio](https://os.mbed.com/studio/)

[Teensy](https://www.pjrc.com/teensy/)

[PSoC](https://www.cypress.com/documentation/development-kitsboards/cy8ckit-059-psoc-5lp-prototyping-kit-onboard-programmer-and)
 
[BeagleBone](https://beagleboard.org/)

IDE universel: [platformio](https://platformio.org/): supporte plus de 800 cartes (dont STM32, Teensy, Arduino, ESP32, PIC32, ...)

## 2.2 Moteurs et controleurs de moteurs

* [Controleur brushless oDrive](https://odriverobotics.com/)
* [LM628/LM629 Precision Motion Controller](http://www.ti.com/lit/ds/symlink/lm629.pdf)
* [Faulhaber](https://www.faulhaber.com/)
* [Maxon Motor](https://www.maxongroup.com/)

## 2.3 Roues

* [JSumo](https://www.jsumo.com/wheels)
* [Fingertech](https://www.fingertechrobotics.com/products.php?cat=Wheels+%26+Hubs)
* [BaneBots](http://www.banebots.com/category/T40P.html)
* [Lynxmotion](https://www.robotshop.com/eu/fr/lynxmotion-roues.html)

## 2.4 Encodeurs

* [rotatif à effet Hall AMS](https://ams.com/angle-position-on-axis)
* [rotatif capacitifs CUI](https://www.cuidevices.com/catalog/motion/rotary-encoders/incremental/modular)
* [rotatif optique Kubler](https://www.kuebler.com/fr/produits/mesure/codeurs/product-finder)
* [rotatif inductif POSIC](https://www.posic.com/EN/products/rotary-encoders.html)
* [LS7366R 32-bit quadrature counter with serial interface](https://lsicsi.com/datasheets/LS7366R.pdf)

## 2.5 Capteurs de distance

* [Capteurs de distance à moyenne portée SICK, laser classe 1 ou 2, ou infra-rouge](https://www.sick.com/fr/fr/capteurs-de-distance/capteurs-de-distance-a-moyenne-portee/c/g176373)
* [Capteurs Time-of-Flight STMicroelectronics](https://www.st.com/en/imaging-and-photonics-solutions/proximity-sensors.html#products)

## 2.6 Pneumatique

* [Coval](https://www.coval.fr/produits/)
* [Piab](https://www.piab.com/fr-FR/Produits/ventouses/)
* [Festo](https://www.festo.com/cat/fr_fr/products)
* [KNF](https://www.knf.fr/fr/produits/pompes-oem/)
* [Thomas Gardner Denver](https://www.gardnerdenver.com/en-us/thomas/gas-pumps)
* [SCHMALZ](https://www.schmalz.com/fr/technique-du-vide-pour-l-automation/composants-pour-le-vide)

## 2.7 Camera pour traitement vidéo

* [OpenMV](https://openmv.io/)
* [JeVois](https://www.jevoisinc.com/)
* [Pixy](https://pixycam.com/)

## 2.8 Sites marchands en vrac

Uniquement mécanique:

* [Misumi](https://fr.misumi-ec.com/)
* [Motedis](https://www.motedis.fr/): profilées alluminuum
* [MakerBeam](https://www.makerbeam.com/): profilées alluminuum

Mixes mécanique/électronique:

* [RS Components](https://fr.rs-online.com/)
* [Pololu](https://www.pololu.com/)
* [RobotShop](https://www.robotshop.com/)
* [Conrad](https://www.conrad.fr/)
* [GoTronic](https://www.gotronic.fr/)
* [Lextronic](https://www.lextronic.fr/)

Modélisme, pour les batteries, chargeurs, moteurs DC, moteurs brushless, controleurs, servos, ...

* [Miniplanes](https://www.miniplanes.fr/)
* [HobbyKing](https://hobbyking.com/)
* [HITEC](https://hitecrcd.com/)

Plutot électronique:

* [Adafruit](https://www.adafruit.com/)
* [Sparkfun](https://www.sparkfun.com/)

Uniquement électronique:

* [Mouser](https://www.mouser.fr/)
* [Farnell](https://fr.farnell.com/)
* [Digi-Key](https://www.digikey.fr/)

Fabricants de circuits imprimés:

* [Aisler](https://aisler.net/)
* [Eurocircuits](https://www.eurocircuits.com/)
* [OSHPark](https://oshpark.com/)
* Comparateur de prix: [PCBShopper](https://pcbshopper.com/)

Service d'usinage:

* [JohnSteel](https://www.john-steel.com/fr/)
* [Usineur.fr](https://www.usineur.fr/)
* [Protolabs](https://www.protolabs.fr/)
* [Xmake](https://www.xmake.com/)


---------------
# 3. Logiciels

## PCB

* [KiCad](https://kicad-pcb.org/): A Cross Platform and Open Source Electronics Design Automation Suite
* [LibrePCB](https://librepcb.org/): A new, powerful and intuitive EDA tool for everyone
* [EasyEDA](https://easyeda.com/fr): Online PCB Design Tool
* [Eagle](https://www.autodesk.fr/products/eagle/free-download)
* [Altium Designer](https://www.altium.com/altium-designer/)
* [Alegro PCB Designer](https://www.cadence.com/en_US/home/tools/pcb-design-and-analysis/pcb-layout/allegro-pcb-designer.html)

outils:

* [PCB panelizer & Gerber tool suite](http://blog.thisisnotrocketscience.nl/projects/pcb-panelizer/), [explication en vidéo par Christian Hortolland](https://www.youtube.com/watch?v=c5XWobI4Eog)
* [gerbv](http://gerbv.geda-project.org/): A Free/Open Source Gerber Viewer

## CAO

* [Fusion 360](https://www.autodesk.com/products/fusion-360/overview)
* [SOLIDWORKS](https://www.solidworks.com/)
* [FreeCAD](https://www.freecadweb.org/)
* [OpenSCAD](http://www.openscad.org/): The Programmers Solid 3D CAD Modeller
* [SOLVESPACE](http://solvespace.com/): parametric 2d/3d CAD


---------------
# 4. Autres liens

## 4.1 Codes sources des équipes

* [CVRA](https://github.com/cvra)
* [Microb Technology](https://github.com/onitake/aversive)
* [ESEO](https://github.com/ClubRobotEseo)
* [EsialRobotik](https://github.com/EsialRobotik)
* [ARIG Robotique](https://github.com/ARIG-Robotique)

## 4.2 Liens en vrac

[Forum Planete Science / Coupe de France de robotique](https://www.planete-sciences.org/forums/)

[Portail des sites web des équipes par PM-ROBOTIX](https://www.pm-robotix.eu/sites-de-la-coupe-et-des-equipes/)

[Elements of Robotics, Mordechai Ben-Ari, Francesco Mondada, 2018, Open Access](https://www.springer.com/gp/book/9783319625324)