Prusa i3 Extruder
-----------------

This is a derivative of Kliment's excellent work on his 'i3ext' project for
the Prusa i3 3D printer.

I have modified it to work with jhead hotends (potentially dual extrusion, 
if stacked vertically), MK7-compatible hobbed pulleys, and variable mount 
hole spacings.

The extruder requires:

* NEMA17 stepper motor

* two 625zz bearings (r4zz's potentially used instead?)

* long M5 bolt, washers, nut

* MK7 hobbed pulley (Makerbot, TrinityLabs, etc)

I have not tested this yet, so consider it highly experimental.

NOTE: 

* main_block.scad: whole drivetrain area is open

* main_block_v2.scad: has config option to open up either the front, back, or 
both idler areas in case you want to stack and selectively use one drive area
over the other.

* do not change the hobb diameter in the top of the config options as this
does not work right yet.


RP one of each:

* main_block.scad or main_block_v2.scad
* idler.scad
* large_gear, small_gear from gears.scad
