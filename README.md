# Flashlight
This is a repository for a flashlight.
It measures Ø54 mm x 223.5 mm depending on the batteries used.
It can be made using a normal lathe and a drill press or a milling machine.
A multi axis CNC is required for the fancy engraving.

You will need a round stock that has 60mm diameter and 240mm length, 
material 6061 aluminium alloy to make this flashlight.
You will need to thread the parts as you see fit, and add knurling.

If Anodizing is added as a surface treatment, the threads must be left bare, as the chassis is DC negative and electric connections must be preserved.

It is also smart to use a good quality  thermal paste on the backside of the LED pcb. Something like NT-H1 from Noctua is good.
Ordinary electric conductive copper paste can perhaps be used on the threads on the part that holds the two PCB's to improve the thermal conductivity.

It takes two 32600 lithium ion batteries Batteries ( 32 mm diameter and 60mm length), I think that protected ones should fit.
It can easily be changed to use 32650 ( 32 mm diameter and 65 mm length) if the 32600 batteries is impossible to get,just edit the flashlight-32mm.FCStd file using Freecad.
You just have to find the pad in the battery holder and add 10mm to it. 
You will need to export the iges files and the blueprints afterwards if that is done,as they will be out of date.
This also includes the fancy tube with engraving.

NOTE: Some of these cells mentioned is also available as LiFePO₄.
Use protected cells!

Note on the LED driver: I dont know if it has any protection agains reverse polarity, but its easy to add that.
Just use this PCB:
https://oshpark.com/shared_projects/fPAPVkXT
It's schematic diagram explains how it's wired up:
https://raw.githubusercontent.com/Supermagnum/polarity/master/schematic.png
It also requires a DC- negative connection, take care so the batterys DC+ side cannot get in contact with the PCB's DC- connection/solder pad.

One leg of the switch must be connected to the endcap. The switch may require a small spring so the other leg is in contact with the batterys negative therminal.

It also needs the parts, those are mentioned inthe BOM file.

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
NOTE: The LED Driver and the LED PCB, and the O-rings and lithium ion batteries are not covered by the mentioned license!



