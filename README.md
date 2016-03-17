SailPi
======

Ansible scripts to setup a fresh Raspberry Pi for the boat _Sophia_.
Current system is:
- RasPi2B+ running Raspbian Jessie Lite 2015-11-21 
- Semi-custom [UPS-like functionality](http://lowpowerlab.com/mightyboost/)
- Ralink 5370 (RT5370 chipset) wifi adapters (2x)
- Specific RS232-USB converters for NMEA0183 instruments 
	- GPS
	- Nexus NX sailing instruments
	- [dAISy](https://github.com/astuder/dAISy) AIS receiver

Todo
====
- [ ] make generic, remove config that is specific to one particular project
- [ ] add gsm connectivity

 Later
- [ ] "MapProxy" cache setup with seeding

Credits
=======

Fork of [original project](https://github.com/hkapanen/sailpi) with the intention of continuing work in this repo.
