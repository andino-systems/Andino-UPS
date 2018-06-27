# Andino-UPS


Andino UPS, a base Uninterruptable Power Supply for 24 Volt DC Client Devices.
It stores the Energy in long lasting Supercaps instead of Lead- or Lithium Batteries.
Depending on the environment temperature, the livetime are up to 10 years without any maintance. 

[Homepage of Andino UPS](https://andino.systems/andino-ups-uninterruptible-power-supply/)

[Andino UPS at the Clear Systems Shop](https://clearsystems.de/shop/product/andino-usv/)

More details about the mode of operation of the [Firmware and how to configure are here](https://github.com/andino-systems/Andino-UPS/tree/master/src)

--- 

![Andino X2 - Raspberry Pi on DIN Rail](andino-ups-small.png)

## Overview

This UPS is designed for industrial PLC and other devices powered with 24 V DC.
It is intended to allow the client device to bridge over short voltage drops and, in the event of a prolonged power failure, to shut down in a controlled manner.

Thus, the controlled device can close databases, connections and synchronize the file system without the risk of data loss.

The Andino UPS has an 24V DC Input and a 24V DC Output. 
This reduce the Energy loos for the conversion to mains power and backwards.

The UPS can deliver up to 10 Watts or 0,4 Ampere at 24 Volts.


## Wiring


![Andino UPS - Wiring](wiring.png)


## EMC Tests

The Andino UPS has been extensively tested for its electromagnetic compatibility (EMC).

The tests were based on the immunity to electrostatic discharge, high-frequency electromagnetic fields, fast transient electrical disturbances (burst), impulse voltages, conducted disturbances – induced by high-frequency fields and magnetic fields with energy-related frequencies.

The tested standards in detail

	Radiated field strength / conducted emissions
	DIN EN 55022: 2011 according to VDE 0875 part 22 of 12.2011
	Störaussendung: Klasse B (Wohnbereich) (strengere Grenzwerte) 
	Störfestigkeit: Klasse A (Industriebereich) herangezogen. (höhere Einstrahlung)
	
	Immunity ESD
	DIN EN 61000-4-2: 2009 according to VDE 0847 part 4-2 of 12.2009
	
	Immunity radiated electromagnetic fields
	DIN EN 61000-4-3: 2006+A1:2008+ A2: 2010 according to VDE 0847 part 4-3 of 04.2011
	
	Immunity Burst
	DIN EN 61000-4-4: 2012 according to VDE 0847 part 4-4 of 04.2013
	
	Immunity Surge
	DIN EN 61000-4-5: 1995 +A1: 2014 according to VDE 0847 part 4-5 of 03.2015
	
	Immunity high frequent uncoupled emission
	DIN EN 61000-4-6: 2014 according to VDE 0847 part 4-6 of 08.2014
	
	Immunity magnetic fields
	DIN EN 61000-4-8: 2010 according to VDE 0847 part 4-8 of 11.2010

## Block diagram

![Andino UPS - Wiring](block.png)

