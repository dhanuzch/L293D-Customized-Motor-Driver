# L293D Motor Driver
This repo consists of a L293D based motor driver compatible with microcontrollers. The main motivation behind this project was because of unavailability of a motor driver that exactly fits in a custom made robot.

## Using Gerber file
Just upload/give this file to online board houses such as JLCPCB or offline board houses, if you are intereseted in printing this PCB.

# Files
 - **[Board](%28https://github.com/dhanuzch/L293D-Customized-Motor-Driver/edit/master/Board/%29)** consists of eagle *project, schematic and board files*
 - **[Images](https://github.com/dhanuzch/L293D-Customized-Motor-Driver/edit/master/Images/)** of board and schematics
 - **L293D_gerber.zip** pre-zipped so it is easy to print the PCBs

## Parts List
|Quantity         |Component Name | Name in schematics|                        
|----------------|---------------|---|
|1|LM317M SMD|**IC3**|
|2|L293D TH |**IC1**|
|4|240ohms SMD|**R1** |
|5|720ohms SMD|**R2** |
|6|1uF SMD|**C4** |
|7|10uF SMD|**C5**|
|8|0.1uF TH|**C3**|
|9|1N4002|**D1**|
|10|1N4002|**D2**|

## Specs
|         |Min | Max |Unit|                        
|----------------|-----|----|---|
|Input voltage(VCC1)||36|V|
|Input voltage(V1)||7|
|Output current|-1|1|A|
|Operating temperature|0|70|°C|

## Disclaimer
Using an offshelf L298N motor driver is a better option if you are dealing with motors that use more than 1A.
