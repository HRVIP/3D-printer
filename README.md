# 3D-printer
Resources, information, lessons learned, configuration files, and any other useful items for the HRVIP MakerGear M2 3D printer

Printer Maintenance
===================

PLA Handling
------------
PLA is water absorbent and must be stored in a sealed bag with desiccant to prevent ruination.
When not in use: store in bag
When in use: consider covering or building a sealed container to allow it to feed while still remaining relatively dry vs. the environment

_**How to tell your PLA is bad:**_

Clean, brand-new PLA will be highly reflective, smooth to the touch, and will bend nearly 180° before breaking
Ruined PLA will have a dull sheen, be rougher to the touch, and will snap at a smaller angle.
If you receive a brand new spool that is contaminated, contact MakerGear support directly and they will replace it.


_**Tangled PLA spools:**_

PLA spools can tangle when the end of the thread crossed underneath a spooled thread, typically just after the end is removed from the machine.
A tangled PLA spool can cause significant physical damage to the machine.
[This video](https://www.youtube.com/watch?v=lE9LchCtKL4) will illustrate how to untangle and unknot your spool if this happens.
Use binder clips and clean paper towels/wipes to prevent tangling in the future, as illustrated in [this MakerGear Forum thread](http://forum.makergear.com/viewtopic.php?f=11&t=2772&p=17361#p17361).


Clogged Nozzle
--------------

Dust and debris can get lodged in the nozzle and reduce, skew, or wholly prevent easy and consistent extrusion.
Use the ‘Cold Pull’ method to clean the nozzle (possibly have to repeat several times).
Old PLA can cause similar symptoms since it absorbs water (see above), which will in turn vaporize inside the nozzle and form bubbles which will resist extrusion
Only replace the nozzle if the Cold Pull method does not work (assuming PLA is good)
DO NOT INSERT ANY FOREIGN OBJECT IN THE NOZZLE IN ATTEMPT TO UNCLOG
Doing so many physically scratch or otherwise damage the nozzle, resulting in poor performance, or worse, introduce even more debris


Replacing Filament
------------------

Suggest performing a ‘Cold Pull’ every time you remove and replace the filament.
Extruder feed gear is slightly misaligned from the nozzle feed hole -- requires a flat, dull tool to gently push the filament perpendicular to the feed path to align it with the nozzle feed hole.
MakerGear official YouTube channel has a tutorial for swapping filament.


Bed Leveling
------------
Three adjustment screws underneath the bed control bed level
The screws are laid out in an isosceles triangle formation. Adjusting one screw will result in the platform rotating about a line formed by the other two screws. Keep this geometry in mind when adjusting the platform.
These control three axes (2 in rotation, 1 in translation)
“Roll” (Rotation about the Y-axis, which fronts “front to back” when facing the printer)
“Pitch” (Rotation about the X-axis, which runs “left to right” when facing the printer)
Vertical height (Z)
Bed leveling is a time-consuming process and may take upward of 1-2 hours if you’re just learning.
Use the process outlined in this video to go about properly leveling the bed
The nozzle should sit approximately 0.1mm above the bed when the Z-axis is zeroed. This distance will be assured by using the paper test outlined in the previous video.
NOTE 1: The adjustment screws tend to shake themselves loose, especially when the printer is performing lots of fast, short movements inducing a large vibration mode. Use a dab of hot glue on the screw heads (after they are adjusted to their desired position) to keep them in place.
NOTE 2: If the bed is level but the zeroed Z-axis distance is incorrect, you can do one of two things:
Raise/Lower the entire bed by adjusting all three screws by the same amount
Raise/Lower the Z hard-stop screw (not recommended)



Print Settings
A configuration file is available which will specify the bed size and print speeds/temperatures. This is only a starting point -- you will need to adjust the settings as needed based on the geometry of your print.
Layer Heights
Curved features generally require smaller layer heights.
Structural features should use smaller layer heights (increases inter-layer adhesion)
Adaptive layer height is a good feature to use and provides good customizability
Min layer height: 0.1mm
Max layer height: 0.3mm
40% infill for non-structural parts
100% infill for structural parts
Temperature
Bed temperature: 70°C
Nozzle temperature: 220°C (If using older spool, raise to ~230°C)
Support Structures
Max speed: 30 mm/s
Suggested pattern: honeycomb
Pattern spacing: 1mm
Overhang: 30%

