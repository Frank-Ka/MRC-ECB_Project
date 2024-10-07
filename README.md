# MRC-ECB Retro-Computing-Project

This is a DIY Project of a **modular** Z80/Z180 Computersystem based on the old style system bus **ECB** with some pin modifications.
The PCB size for modules is 100x100mm for low cost manufacturing, but also 160x100mm is possible.

The designs on this project site are generally open. You can recreate them yourself or modify them if
you wish. The documentation, schematics, printed circuit board Gerber ﬁles of the MRC-ECB modules will be placed next on this repository.

![plot](https://github.com/Frank-Ka/RC-ECB-64-Project/blob/main/Core-system-5-Slot.jpg)

The backplanes ready to use on table or mounting in a 3HE rack frame for stable mechanic.
The Backplanes in 5 and 7 slot Version tested, a 12 slot backplane work is in progress

The main system circuitry and port mapping based on stephen cousin's open source sc700 project on "smallcomputercentral.com"
So the MRC-ECB computer system is ready to run ROMWBW, SCM, CP/M, Basic and more.
 
The main system consists of four core modules
- CPU with MMU
- MEM with 512k ROM and 512k RAM
- SIO for terminal communication
- CF Card interface
and a backplane to put all together.

Some more modules, such as FDC, RTC, DIO, Sound interface and VGA terminal card are being tested at this time.

![plot](https://github.com/Frank-Ka/RC-ECB-64-Project/blob/main/Rack-system-7-Slot.jpg)
