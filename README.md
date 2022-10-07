# Redshift 

This is the central repository for work on the Redshift PCB.

## Features
- 8kHz polling (USB 2.0 HighSpeed)
- usb-C port
- PAW 3399

## Usage
- KiCad 6.0+ must be installed
- Openinput library from kicad content&lib manager in KiCad

**NOTE:** Encoder 3d file is intentionally not included. If you wish to add it, models are freely downloaded from Alps Alpine [website](https://tech.alpsalpine.com/e/products/cad.html) under EC10E.

## Board Notes
- If connecting USB and debug connectors at the same time, ensure debug supply voltage is under 5v. (some JTAG debuggers have this) 5v supply from debug pins are OK as long as USB is unplugged.

### Credits
A huge thanks to openinput for their generic [KiCad lib](https://github.com/openinput-fw/openinput-kicad-library), as well as their [fully developed PCBs](https://github.com/openinput-fw/sammy) which this PCB is largely based off of.

![2d view of PCB](imgs/d2_v0.png?raw=true "Title")
![3d view of PCB](imgs/d3_v0.png?raw=true "Title")

tests
