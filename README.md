# Flashlight
This is a repository for a flashlight.
It measures Ø54 mm x 223.5 mm

You will need a round stock that has 60mm diameter and 230mm length, 
material 6061 aluminium alloy to make this flashlight.
You will need to thread the parts as you see fit, and add knurling.

If Anodizing is added as a surface treatment, the threads must be left bare, as the chassis is DC negative and electric connections must be preserved.

It is also smart to use a good quality  thermal paste on the threads of the part that holds the driver PCB,LED pcb, and the backside of the LED pcb. Something like NT-H1 from Noctua is good.

It takes two 32600 Batteries, I think that protected ones should fit.

Note on the LED driver: I dont know if it has any protection agains reverse polarity, but its easy to add that.
Just use this PCB:
https://oshpark.com/shared_projects/fPAPVkXT
It also requires a DC- negative connection, take care so the batterys DC+ side cannot get in contact with the PCB's DC - connection/ solder pad.

One leg of the switch must be connected to the endcap. The switch may require a small spring so the other leg is in contact with the batterys DC- therminal.

It also needs these parts, copied form the BOM file:

WÜRTH 	Art.-no. 046803830 	2 	O-ring : RG-O-ISO3601-PERBUNAN70-38,00X3,00
Freudenberg Sealing Technologies/ Otto Olsen 	FKM/FEP MOQ 11 	1 	FEP-O-Seal ID 39,34 X 2,62 FKM
Mountain Electronics 	ARLENS-42MM 	1 	42mm AR Coated Glass Lens
Mountain Electronics 	RFLCTR-42x31.5-OP 	1 	C8 Orange Peel Reflector - 42*31.5mm
Mountain Electronics 	MTN-30DDm-2S+-CLK 	1 	30mm FET + 7135 Driver - MTN-30DDm - 2S-4S Input Voltage (Clicky)
Mouser 	Mouser No: 999-P5-V52122 	1 	Pushbutton Switch, IP69X
Mountain Electronics 	XHP70.2-M4-3K 	1 	Cree XHP70.2 M4 3000K 80+ CRI, 6V 20mm Sinkpad Copper Direct-Thermal-Path

Explanation on the files:
Exploded.jpg is the exploded view from Freecad, with all the parts visible.
Viking-holder.png is the battery holder with graphics from a sword hilt found at Alm in Stange, Norway. It's from around year 800.

flashlight-32mm.FCStd , this is the Freecad file without any fancy engraving.

The Freecad file for the battery holder with fancy engraving is here:
https://www.dropbox.com/s/gc08t12z3uo25pi/viking-holder.FCStd?dl=0


The iges file for that is in this link,because github cannot handle files of that size:
https://www.dropbox.com/sh/lizazcrzlvrs3z1/AABt5q_hpzIwJAGmto8MnXZPa?dl=0


All the IGES files and SVG blueprints are in their folders.

The license for usage and so forth is in:
https://github.com/Supermagnum/Flashlight/blob/master/LICENSE


