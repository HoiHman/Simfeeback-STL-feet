## Usage

***

## Profiles
Every supported game can have one or more profiles which define how the Actuators should move. 
You can have a profile for every Car/Road combination which you like.
Right click and you can copy an existing one, delete or activate it.
Left Click on it and you can rename it 

***

## Effects
_**Tactile Effect**_ sends Data to a Shaker or buttkicker

_**Heave Effect**_ All four Actuators go synced up or down at the same time

_**Pitch Effect**_ The two actuators in front go down (up) and the 2 in the back go up (down). Used in Pitch and Surge.

_**Roll Effect**_ The two actuators on the left go down (up) and the 2 on the right go up (down). Used in Roll / Sway / Traction loss

_**Rumble(all)**_ Data like RPM will be available on all 4 actuators as vibrations 


***
_**Example Effect and description of Values**_ 

![Heave Effect](https://github.com/SimFeedback/SimFeedback-AC-Servo/blob/master/HeaveEffect.png)

* Linear - if checked its a lot rougher :)
* Name - Name of the Effect (Heave)
* Telemetry Key - Choose the Key which will be used to create the Effect  (VertAccel)
* Min Position - Percentage used of the way the actuator can move (-100) / Heave uses ~22 Percent of the Actuator if the value -3 is reached    
* Max Position - Percentage used of the way the actuator can move (100) / Heave uses ~22 Percent of the Actuator if the value 3 is reached
* Position Interval - Interval which Position is divided (20)
* Min. Power - 
* Max. Power
* Power Interval
* Enabled
* Mute
* Smoothing
* Controller ID.
* Intensity

## **Add Effect**
Right click on your profile and choose Add Effect -> Choose the one you like ..

