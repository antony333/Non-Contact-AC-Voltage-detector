# Non-Contact-AC-Voltage-detector
The objective of this project is to create a non-contact AC voltage detector on a PCB board.

https://user-images.githubusercontent.com/72541715/128242127-0ad2d9b1-51a4-4d22-9144-a7d4ea4d7757.mp4

## Softwares Used
**LT Spice  
KiCad** 

## Components
**NPN Transistor  
Resistor  
LED  
Buzzer  
Antenna  
Battery**

## Processes Involved
The circuit was initially simulated on LT Spice and the PCB layout was designed using KiCad. Drilling and etching processes were carried out manually.


## Working
The principle behind this device is electromagnetic induction. A magnetic field is produced around a current-carrying conductor and if the current through the conductor is AC the magnetic field produced varies periodically. When we place an antenna near an AC energised object, a small current gets induced in the antenna and activates the first transistor. The output of the 1st transistor drives the 2nd transistor, it gets activated, and so on. As the 3rd transistor is activated LED is turned ON and the buzzer starts beeping indicating the presence of AC Voltage.   

![image](https://user-images.githubusercontent.com/72541715/128242677-93cf1e45-3131-45b3-a356-eca9a139711a.png)

![image](https://user-images.githubusercontent.com/72541715/128242735-4cfff8c7-87cf-408d-af48-c9e8e6833463.png)
