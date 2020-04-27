# Drone-setup-with-Ardupilot
Setting up a Quad-copter using Ardupilot  (APM2.8).

Guide & Caution

1. Any of the propeller should not attach during calibration.

2. During the RC calibration ... the switches and trimmer buttons 
   should be as it is.

3. GPS calibration should be done outside of the room. (at Sats: 14-15)

4. GPS stand have to use otherwise, there may occur interference error.

5. To fix CW and CCW rotation, interchange the red and black wire of the
   motor during *Motor test.

6. After calibration unplug & plug in the cable.

7. RED light glow continuously, when armed.

8. ESC should be good quality (30Amp min) otherwise drone will not stabilize
   properly. Automatically may move towards LEFT/RIGHT/FORWARD/BACKWARD 
   (even on Loiter mode).

9. Every time after Drone-crash recalibrate the drone before flying. 
   (Because after crashing there may occur memory loss of controller)

10.GPS_glitch is very problematic issue, due to this issue drone get wrong
   GPS value and to reach another position, the drone crash very badly. 
   To overcome the problem, sometimes we use two GPS (we have to check the 
   Flight controller support two GPS or not) or prime quality GPS.

....................Recommended parts for this Quad-copter ........................................................................ our drone.......................................

<img src="APM_component.png" height=350> <img src="our drone.jpg" height=350>

Propellor Setup

<img src="Propellor setup/Motor Position & Direction.jpg" width=400> <img src="Propellor setup/propellor_setup guide.jpg" width=400> 
