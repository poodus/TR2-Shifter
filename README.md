# TR2-Shifter
A circuit board design for a custom hotrod gear indicator. Designed in KiCad.

# What it's for
The car is a lakester-style Model A Ford hotrod, with a Pontiac Solstice ECOTEC swap. It uses an automatic transmission and a highly modified ECU, so there's currently no indication of what gear you're in. This project is an attempt to solve that by optical means, largely separate from the rest of the car's electronics (except DC power input).

# How it works
A single IR LED is connected to the gear shift handle.

An array of IR detectors sits along the base of the shifter. As the emitter passes over different diodes, LEDs illuminate on a panel to indicate which gear the car is in.

This board powers the above components, and uses two LM339 Voltage Comparators to illuminate the LEDs.

A potentiometer is used to set a reference voltage for the comparators.

# Parts list (unfinished)
2 - LM339 Voltage Comparators, 14pin DIP
2 - JST 14pin PHD connectors
2 - JST 2pin PH connectors
1 - 3mm LED (power on)
1 - small potentiometer

Concept: Vice Chief http://www.vicechief.com
Board design: me, Shane Reetz. 2021.
