### GCC-3v-Cellphone-Rumble
3v Cellphone Rumble for the GCC and Phob GCC project.

## An open source Bracket for the Phob GCC with...
 - NEW design option for 3v Buck Converter
 - Mouse click L/R compatibility 
 - Cutout for OEM and snapback mod wires
 - L-cut hole for phob 1.2.X teensy pins
 - Cell rumble mount with screw on lid
 - Made for easy printing on FDM printers
 - Open Source! Just throw me some credit on derivatives @abeartus :)
 - Shap3r editable files included!
 
## Two Different Models

# Buck Converter Model
 
 ![Alt text](./images/UB3V-Buck-FULLTOP.png)
 
 - Uses a Buck convertor to step down the 5v to 3.3v
 - Bit more involved to construct
 - More consistent 3.3v 
 - Has a funny little light when it vibrates



# Classic Style Model
 
 ![Alt text](./images/UB3V-Classic-FULLTOP.png)
 
 - Needs a roughly 25 ohm resistor to step down the 5v to 3.3v 
 - Easy assembly
 
## required parts
 - M1.6 Heat inserts
     - https://www.mcmaster.com/92120A150/

 - M1.6 Screw 
     - https://www.mcmaster.com/90910A901/

 - 3v cellphone motor
     - https://a.co/d/5HEyPMW

 - 25ohm resister **OR** buck module 
     
	 - https://a.co/d/hcY47oe
     
	 - https://a.co/d/4aCmpb3

# guide

 (1) print the lid(s) and bracket ideally with PLA+

 (2) push in the heat inset screw inserts into the board with a soldering iron on the lowest temperature

 (3) put the motor (and Buck converter if you choose that model) in the housing and screw on the lid(s)

 (4) a) attach a ~25 ohm resitor to the positive motor lead
    OR
     b) [WIP] connect the buck converter to 3v lead and ground

 (5) a) attach the positive lead with the resiter, and ground line to the pcb
    OR
     b) [WIP] connect the 5v and ground lines on the buck converter to the pcb

 (6) Put the bracket in place and screw it to the PCB. Done

 - similar guide by fires on his bracket, mines is pretty much the same so credit to fires 
    - https://firescc.com/mod-guides#/rumble-bracket