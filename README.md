# Ender 5 Plus - Upgrade to a Big Tree Tech SKR 1.4 Turbo Board, with BTT TFT35 E3 V3.0 Display
Notes from upgrading the Creality Ender 5 Plus to a BTT SKR 1.4 Turbo board, with a BTT TFT35 E3 V3.0 Display.
This is NOT a "how-to", this is notes from my upgrade experience so that other people can get help or learn from it.

-	TMC2209 drivers in UART mode, with the diag pin cut, so not using sensor-less homing (i.e. using the standard end-stop switches).
-	BL Touch (v3.1) fully working. NB: If you want to use sensor-less homing, this will not work on the Z-axis, please see the section below on the BL Touch.
-	Display working in both “touch screen” mode and “marlin” mode (you can change between the modes at any time). There are some minor problems related to display firmware, with the version of firmware used at the time of this build.
-	Using original case (for now) with mounting adapters etc.
-	Using Cheetah 5 firmware (at the time version 1.3.4) for SKR 1.4 Turbo board. NB: This firmware does not work with the stock Ender 5 Plus display.
-	Using BTT TFT35 V3 firmware for display (at the time version V3.0.25.3).
-	Direct Drive Extruder (previously done mod) using the Micro Swiss direct drive and Micro Swiss hot-end (this requires some mechanical changes to fit it correctly which ends up with needing to invert the x-axis stepper direction in configurations).
-	Hero-Me Gen 3 fan ducts replacement (Ender 3 variant due to the Micro Swiss direct drive upgrade as well, mod done previously).
-	Awesomely quiet steppers now!!! – just need to do the fans next and then we’ll have a really quiet machine. 
-	We did encounter a problem I think is related to EMI noise on the cabling due to how they are routed, discussed in this document along with how it was fixed in the Issues section.

