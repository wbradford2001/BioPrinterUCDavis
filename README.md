# BioPrinterUCDavis
3D BioPrinter Marlin Configuration UC Davis

# Overview
upload file "CONFIGURED_OCT_25" to arduino to control a bioprinter that aims to be able to print transgenic protein in a cellular matrix. 

# Instructions
For all intents and purposes, "configuration.h" and maybe "configuration_adv.h" are all that we care about. In these files we edit and input the parameters of the printer(width, height, ect...) that tell the arduio how to move, how much to extrude, ect..

#NOTE:
The kinematics need to be configured to properly move the extruder and extrude a specified amount
