***
> **WICHTIG / IMPORTANT**  
Since we have no centering through search and get alarms its necessary that the actuators are complete down.
Step on every corner and then they will roll down if you are not sure if they are.
***

## Getting started / Setup

### **_Tactile_**
* Setup the Soundcard were youre shaker is attached. At the moment we support only one. 
* Press play and move the sliders, you will hear if you have chosen the right one.
* Mount it under your seat or direct to the seat or whereever you think it suits your needs :)

![Setup Shaker](https://github.com/SimFeedback/SimFeedback-AC-Servo/blob/master/Docs/SetupShaker.png)

### **_Arduino_**
1. First you have to flash a supplied Hex file to the Arduino which can communicate with the software 
2. Choose correct com port and click Datei auswählen
3. Browse to the hex file which you want flash (for example ACServo_Leonardo_00_07_05.hex) and press upload

![Flashing Arduino](https://github.com/SimFeedback/SimFeedback-AC-Servo/blob/master/Docs/Flashard.png)


> **WICHTIG / IMPORTANT**  
Since we have no centering through search and get alarms its necessary that the actuators are complete down.
Step on every corner and then they will roll down if you are not sure if they are.
 
***

## Actions 
![Actions](https://github.com/SimFeedback/SimFeedback-AC-Servo/blob/master/Docs/Actions.png)
### **_START/ STOP Button_**

If you have read and finished the setup things you should be able to startup the actuators. Press the START button and they will goto center position if everything is good :) 

The Button changes to STOP, wait some seconds and press stop, the actuators are going to park position. This should be really soft for the last mm :)

Start the game you like, activate your profile of it (see below) and press the start button. Go on track and it should move

### **_Realtime Data_**

Activate it and you will see the live telemetry values in every enabled Effect. I prefer one by one effect ..
![](https://github.com/SimFeedback/SimFeedback-AC-Servo/blob/master/Docs/Realtime.png)


### **_Replay_**
* Press Replay and search your recorded session File, press replay .. It should start moving your rig as recorded :) 

### **_Log Data_**
* Activate it and the motion of the session you are driving will be saved in the log folder.

***


## Profiles
* Every supported game can have one or more profiles which define how the Actuators should move. 
* You can have a profile for every Car/Road combination which you like.
* Right click and you can copy an existing one, delete or activate it.
* Left Click on it and you can rename it 
* ![Profiles :)](https://github.com/SimFeedback/SimFeedback-AC-Servo/blob/master/Docs/Profile.png)

***

## Effects
_**Tactile Effect**_ sends Data to a Shaker or buttkicker

_**Heave Effect**_ All four Actuators go synced up or down at the same time

_**Pitch Effect**_ The two actuators in front go down (up) and the 2 in the back go up (down). Used in Pitch and Surge.

_**Roll Effect**_ The two actuators on the left go down (up) and the 2 on the right go up (down). Used in Roll / Sway / Traction loss

_**Rumble(all)**_ Data like RPM will be available on all 4 actuators as vibrations 

***
_**Example Effect and description of Values**_ 

![Heave](https://github.com/SimFeedback/SimFeedback-AC-Servo/blob/master/Docs/HeaveEffect.png)
 
* **Linear** - if checked its a lot rougher :)
* **Name** - Name of the Effect (Heave)
* **Telemetry Key** - Choose the Key which will be used to create the Effect  (VertAccel)
* **Min Position** - Percentage used of the way the actuator can move (-100) / Heave uses ~22 Percent of the Actuator if the value -3 is reached    
* **Max Position** - Percentage used of the way the actuator can move (100) / Heave uses ~22 Percent of the Actuator if the value 3 is reached
* **Position Interval** - Interval which Position is divided (20)
* **Min. Power** - Range of values given by the simulation. Here 0 to -3g
* **Max. Power** - Range of values given by the simulation. Here 0 to 3g
* **Power Interval** - Interval which Position is divided (0,25)
* **Enabled** - if true -> then enabled 
* **Mute** - nevermind
* **Smoothing** - Value given by the smoothing Slider
* **Controller ID.** - Controller # used 
* **Intensity** - Value give by the Intesity Slider

## **Add Effect**
Right click on your profile and choose Add Effect -> Choose the one you like ..

