# 3A_BREAK

## Components
* MOSFET de puissance, Canal N, 100 V, 31 A, 0.031 ohm, TO-263 (D2PAK), Montage en surface :  
https://fr.farnell.com/nexperia/buk9637-100e-118/mosfet-n-ch-100v-31a-d2pak/dp/2254193

* Régulateur à découpage Buck (Step Down), Fixe, Entrée 7.5V à 76V, Sortie 5V 500mA 125 kHz NSOIC-8 :  
https://fr.farnell.com/maxim-integrated-products/max5033busa/convertisseur-dc-dc-buck-125khz/dp/2513947

* Redresseur Schottky, 100 V, 2 A, Une, DO-220AA, 2 Broche(s), 800 mV :  
https://fr.farnell.com/vishay/ss2ph10-m3-84a/diode-rectifier-schottky-2a-100v/dp/1812489

* WE-PDA SMT Shielded Power Inductor EXTENDED - 784771221 - 220uH 0.99A :  
https://www.we-online.com/catalog/en/WE-PDA?sq=784771221#784771221

* Carte de développement, MCU Nucleo-G431KB, STM32G431KBT6U, Arduino Nano V3 :   
https://fr.farnell.com/stmicroelectronics/nucleo-g431kb/carte-de-dev-32-bits-arm-cortex/dp/3132398

* Bornier fil-à-carte, 5.08 mm, 2 Voies, 26 AWG, 12 AWG, 4 mm², Par vis :  
https://fr.farnell.com/multicomp/mc000034/bornier-ci-noir-5-08mm-vis-02/dp/2008004

* CI Driver de MOSFET, Low Side, Alimentation 4.5V à 16V, 2A Out, 35ns Retard, SOIC-8 :  
https://fr.farnell.com/microchip/tc1412neoa/driver-mosfet-2a-non-inv-8soic/dp/1834898

* Redresseur Schottky, 60 V, 15 A, Une, TO-263AB, 3 Broche(s), 620 mV :  
https://fr.farnell.com/vishay/vs-15tq060s-m3/diode-schottky-simple-60v-to263ab/dp/2909608

* Codeur rotatif, Mécanique, Incrémental, 15 PPR, 30 crans, Verticale, Avec commutateur push :  
https://fr.farnell.com/wurth-elektronik/482016514001/codeur-rotatif-mecanique-incremental/dp/3806131?ost=3806131

* Afficheur LCD, Grove, LCD RGB 16X2 rétroéclairage, Interface I2C :  
https://fr.farnell.com/seeed-studio/104030001/grove-cran-lcd-rvb-r-tro-clair/dp/3932101

## Tools

* Calcul isolement :  
https://www.smps.us/pcbtracespacing.html



## Export Gerber 

CAM Processor
CAMOutputs

### LPKF
* Switch on LPKF
* Open LPKF CircuitPro PM 2.7 software
* Wait few minutes
* Choose Template DoubleSided_Galvanic_THP
* Check Machining -> Connect... (if not) -> S62
* Calibration Key is incorrect -> ok
* Import Data from a non-native format 
* -> Import all gerbers and drillfiles
* Generate isolation and contour -> 35um
* Process -> 4/4

### Photo-ploter
* Gerb2BMP : 
* Import Master Gerber
* Copper_Top // Copper_botton
* Export Gerber to bitmap file (2032 dpi)

* Filmstar : Generate and run on photoploter
* CUIVRE : NEGATIVE !!!
* 


