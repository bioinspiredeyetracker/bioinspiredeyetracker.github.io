---
layout: post
author: Jorge Villazon
---

**Objective:**
The objective of redesigning the qDVS Printed Circuit Board (PCB) is to create a proof-of-concept for a implementing the qDVS on a mobile eye-tracking system on a marmoset. To be feasible, this design should be relative low in weight and size, such that the marmoset can wear it for extended periods of time without it becoming obstructive to the experiment.

**Redesign Procedure:**

_Conceptualization:_

To first redesign the PCB of the qDVS, we had to 

_Drafting a Schematic:_

The projector PCB shield and corresponding code were used to turn on the projector. To perform the optical canned experiment, we first experimented with projector and screen position via a "strobe light" video found on Youtube. In doing so, we altered the position of both the projector and screen while the video was playing to determine the optimal position. Specifically we wanted the entire projector video frame to take up as much space on the projector screen as possible, and we wanted to ensure that the image was clear and in focus. We also attempted to minimize the degree of glare on the screen as we observed it could cause significant noise in the data.

For this test, we projected our Unity eye movement videos at our highest physiological speed of 72 degrees/sec. We projected videos recorded with 100%, 75%, 50%, and 25% brightness levels. An example of two output frames is shown below.

Unfortunately, due to the relatively low sensitivity of the older version of the qDVS that we had available to test, we were not able to obtain meaningful quantitative eye gaze vector results from our testing.  However, we did observe a general trend between the percentage of illumination and the ability of the qDVS to pick up clear event frames. As brightness increased, there was a higher percentage of readable event frames. Specifically, at the brightness level of 25%, 0 of the output frames contained both on and off events and resembled the circular shape of an eyeball; whereas at a brightness level of 100%, over 50% of output frames contained both types of events.

For more meaningful results, these experiments should be replicated with the newer, highly sensitive version of the qDVS which will arrive at the Cauwenberghs lab in spring of 2022.

_Creating a PCB on Altium:_
