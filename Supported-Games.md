SimFeedback supports the following games:

* iRacing
* Assetto Corsa
* Project Cars 1 and 2
* Dirt Rally

## Setup Instructions

### iRacing 

Edit app.ini in C:\Users\USERNAME\Documents\iRacing.


`irsdkEnableMem=1                        	; enable memory based telemetry`

`irsdkLog360Hz=1                         	; Log some telemetry at 360 Hz rather than at 60 Hz`


### Dirt Rally
Edit hardware_settings_config.xml  in C:\Users\USERNAME\Documents\my games\DiRT Rally\hardwaresettings.

`<udp enabled="true" extradata="3" ip="127.0.0.1" port="20777" delay="1" />`
