# Klippventurer-mods
!!IN PROGRESS!!

This is my contribution to the Klippventurer project.
A big thank you to The-Synthax for being involved in this project by giving us the opportunity to replace the firmware of this printer by Klipper.
Check out here: https://github.com/synthread/Klippventurer

In my Adventurer 3 printer upgrade process, the next step after upgrading the operating system to Klipper (Klippventurer) is to replace the extruder.
I had an old Voron Clockwork extruder lying around.  So I decided to go from there.
The result is an extruder whose internal parts are those of the Clockwork but whose fasteners are modified.

Printing:

The printing parameters are those prescribed by Voron: ABS, layer height 0.2mm, extrusion width 0.4,
filling 40%, grid type filling..., walls 4, upper/ lower layers 5 and no support.
For the legs I suggest a skirt.  Cut the parts in triangle.  These are supports.

Hardware and assembly:

The hardware and assembly is essentially the same as Voron’s:
https://github.com/VoronDesign/Voron-Afterburner/blob/afterburner/Manual/Afterburner.pdf
The main differences are the attachment of the legs and an ECAS coupler.
I did an adapter to connect the motor.
The target is held by 2 3x6mm magnets. 

Config:
You'll have to modify your 
rotation_distance: 39.461375 and
gear_ratio: 50:10
