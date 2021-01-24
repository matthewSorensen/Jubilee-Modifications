# Warp-Resistant Hemera Jubilee Tool

This is a derivative of [Bryan Haven's Hemera tool](https://github.com/BryanHaven/Jubilee-Hemera-Tool-Mount), with the following modifications:

* Delrin locking plate is rotated 60 degrees. Early testing shows that this alone significantly reduces plastic creep at room temperature,
      but the long-term efficacy for heated tools is unknown.

* The addition of a 0.1" laser cut aluminum (7075 T6) spacer between the Hemera body and the mounting plate. This should improve thermals
      and significantly reduce the stress on the plastic mount - my experience is that the section of the tool plate previously supported by
      the extruder body didn't deform at all, and the creep was limited to the area around the unsupported mounting ball.

* Countersinks are 0.5mm deeper, to accommodate the stack up of 10mm mounting bolts and the extra 2.54mm spacer.


## Fabrication and Assembly

Print *ModifiedHemeraPlate.stl* in PLA, with 6 perimeters and 25% infill in the provided orientation. I sourced the aluminum spacer from 
[OSHCut](https://www.oshcut.com/), in 0.1" Aluminum 7075 T6 - roughly $4/per + $20 setup charge.


Assemble heated insert nuts, delrin lock plate, and the two mounting balls with countersinks as normal. The third mounting ball attaches
with a M3x10 (or M3x8) button head screw fastened through the aluminum plate. Critically, the Hemera body requires 3 M3x10 socket head
caps screws, instead of the stock M3x8 length.

Tool wings and cable management are unchanged.