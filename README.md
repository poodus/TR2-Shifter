# TR2-Shifter
A circuit board design for a custom hotrod gear indicator. Designed in KiCad.

# HOW IT WORKS
A single IR LED is connected to the shift handle of an automatic transmission. This heavily customized car uses a Pontiac Solstice ECOTEC engine / transmission inside of lakester-style Model A Ford body.

An array of IR detectors sit along the base of the shifter. As the emitter passes over different diodes, LEDs illuminate on a panel to indicate which gear the car is in.

This board powers the above components, and uses two LM339 Voltage Comparators to illuminate the LEDs.

A potentiometer is used to set a reference voltage for the comparators.

# PARTS LIST (unfinished)
2 - LM339 Voltage Comparators, 14pin DIP
2 - JST 14pin PHD connectors
2 - JST 2pin PH connectors
1 - 3mm LED (power on)
1 - small potentiometer

Concept: Vice Chief http://www.vicechief.com
Board design: me, Shane Reetz. 2021.
