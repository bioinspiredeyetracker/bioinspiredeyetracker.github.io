---
layout: post
author: Jorge Villazon
---

**Objective:**
The objective of redesigning the qDVS Printed Circuit Board (PCB) is to create a proof-of-concept for a implementing the qDVS on a mobile eye-tracking system on a marmoset. To be feasible, this design should be relative low in weight and size, such that the marmoset can wear it for extended periods of time without it becoming obstructive to the experiment.

**Redesign Procedure:**

_Drafting a Schematic:_
To create a proof-of-concept for the device that are viable for being placed on the on the marmosets within the Cortical and Behavioral Systems Laboratory, namely the device should be small and light enough for the 1 foot-long primates to wear on their back and their head. The current qDVS design, known as the qDVS 5, is too large and heavy for it to be supported by the body of the marmosets. If this were the case on the actual device, then the cognitive experiments on these marmosets would be incredibly impacted as their movement and behavior would be different if they were under the weight of a large device.

With assistance from the Integrated Systems Neuroengineering, a design that could meet this requirements was constructed by modifying the existing schematic to instead separate the two "stacked" boards of the qDVS 5 into a "top" and "bottom" board. The "top" board of this new design would house the socket for the imager used for capturing light from the eyes of the marmoset as well as the chip responsible for detecting the light intensity changes. The "bottom" board would contain the current "back-end" components that underly the neurmorphic design of the qDVS 5. These two boards would then be connected via a ribbon cable and two ZIF connectors on each board. Once the design was conceptualized, a schematic was created on Altium Designer, a PCB automation software, for the top board, consisting of the ZIF connector and the imager chip.

_Creating a PCB on Altium:_

After creatin
