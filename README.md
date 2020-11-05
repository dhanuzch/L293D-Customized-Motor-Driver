
# L293D Motor Driver
This repo consists of a L293D based motor driver compatible with microcontrollers. The main motivation behind this project was because of unavailability of a motor driver that exactly fits in a custom made robot.

## Using Gerber file
Just upload/give this file to online board houses such as JLCPCB or offline board houses, if you are intereseted in printing this PCB.

## Files
 - **[Board](https://github.com/dhanuzch/L293D-Customized-Motor-Driver/edit/master/Board/)** consists of eagle *project, schematic and board files*
 - **[Images](https://github.com/dhanuzch/L293D-Customized-Motor-Driver/edit/master/Images/)** of board and schematics
 - **L293D_gerber.zip** pre-zipped so it is easy to print the PCBs

## Parts List
|Quantity         |Component Name | Name in schematics|                        
|----------------|---------------|---|
|1|L293D TH |**IC1**|
|2|LM317M SMD|**IC3**|
|3|1N4002|**D1**|
|4|1N4002|**D2**|
|5|240ohms SMD|**R1** |
|6|720ohms SMD|**R2** |
|7|0.1uF TH|**C3**|
|8|1uF SMD|**C4** |
|9|10uF SMD|**C5**|
|10|Connectors-KF301|**X1**|

## Specs
|         |Min | Max |Unit|                        
|----------------|-----|----|---|
|Input voltage(Vcc1)|4.5|7|V|
|Input voltage(Vcc2)|4.5|36|V|
|Output current|-1|1|A|
|Operating temperature|0|70|°C|

*Vcc1* -  Voltage for internal logic translation<br>
*Vcc2* -  Voltage for drivers

It is also advisable to use heatsink to increase the lifespan of the IC.

## Disclaimer
Using an offshelf L298N motor driver is a better option if you are dealing with motors that use more than 1A. 
