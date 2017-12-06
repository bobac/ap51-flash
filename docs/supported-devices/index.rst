=================
Supported devices
=================

In general you can flash all devices which use the redboot bootloader that has
the reflashing function enabled. ap51-flash will automatically detect redboot
when you turn on the device. If your device is not in the "known to work" list
which follows you still can try it and inform us about the result.


redboot devices
===============

* FON, La Fonera (2100)
* Open Mesh, OM1P
* Engenius, EOC-1650, EOC-2610, EOC-2610p
* Engenius, 3660
* Dlink, DIR-300 (after installing a reflash-enabled redboot)
* Ubiquiti, Pico2 & HP
* UniAppliance Colibrì (!UniData)


tftp flash
==========

ap51-flash also supports plain tftp flashing without redboot. This method is
quite common amongst a variety of devices.

List of known to work tftp devices:

* Ubiquiti, NanoStation2
* Ubiquiti, NanoStation5
* Ubiquiti, Bullet2 & HP
* Ubiquiti, RouterStation


u-boot flashit
==============

List of known to work uboot devices:

* Open Mesh, OM2P, MR500


other devices
=============

There are many different devices out there which differ slighty in their way of
doing things. Even if your device does not work out of the box it might require
only small changes to support it.