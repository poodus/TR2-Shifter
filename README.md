# TR2-Shifter
A circuit board design for a custom hotrod gear indicator. Designed in KiCad.

# What it's for
The car is a lakester-style Model A Ford hotrod, with a Pontiac Solstice ECOTEC swap. It uses an automatic transmission and a highly modified ECU, and as a result there's no obvious indication of what gear you're in. This project is an attempt to solve that by optical means, largely separate from the rest of the car's electronics (except DC power input). This concept and the other fabrication work is done by Vice Chief http://www.vicechief.com

# How it works works
An off-board buck converter steps 12V from the car down to 5V. 

A single IR LED is connected to the gear shift handle.

An array of IR detectors sits along the base of the shifter. As the emitter passes over different diodes, LEDs on a separate panel illuminate to indicate which gear the car is in.

This board powers the above components, and uses two LM339 Voltage Comparators to illuminate the LEDs.

A potentiometer is used to set a reference voltage for the comparators.

# Parts list (unfinished)
2 - LM339 Voltage Comparators, 14pin DIP
2 - JST 14pin PHD connectors
2 - JST 2pin PH connectors
1 - 3mm LED (power on)
1 - small potentiometer


Board design by Shane Reetz. 2021.
