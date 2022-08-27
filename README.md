# Marlin 3D Printer Firmware

![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
![GitHub contributors](https://img.shields.io/github/contributors/marlinfirmware/marlin.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/marlinfirmware/marlin.svg)
[![Build Status](https://github.com/MarlinFirmware/Marlin/workflows/CI/badge.svg?branch=bugfix-2.0.x)](https://github.com/MarlinFirmware/Marlin/actions)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

Additional documentation can be found at the [Marlin Home Page](https://marlinfw.org/).
Please test this firmware and let me know if it misbehaves in any way. 

 2.0 bugfix https://github.com/pharscape22/SKR-mini-E3-V3.0-Marlin/tree/SKR-mini-E3-V3.0-G0B1-Marlin-bugfix-2.0.x
 A clone of the Bigtree branch tested with Bigtreetect TFT35-E3 V3.0.1 LCD
 Working on my Aquila X2 
 
 2.1 bugfix https://github.com/pharscape22/SKR-mini-E3-V3.0-Marlin/tree/SKR-mini-E3-V3.0-G0B1-Marlin-bugfix-2.1.x
 Branch from Marlin 2.1.x bugfix.
 Used with Bigtreetect TFT35-E3 V3.0.1 LCD
 Working on my Aquila X2 

Major Configuration changes to be aware of:
Build plate is set to 220 x 220
Build height is 230
Custom PID tuning to match my hotend (not Ender defaults).
E-steps is for a dual gear extruder @ 139.8mm/sec vs stock Ender 93
Homing speeds are faster.
Bltouch Probing is 5x5 High Speed, single probe with accelerated X,Y,Z movement. 
