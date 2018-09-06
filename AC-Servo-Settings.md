## AC Servo Settings

Get familiar with the control schema (Arrows, MOD, SET).

Push MOD until you see Pn000. This is the parameter mode.

Change and control these settings on all motors:

P8 = 300 
P9 = -300 
P51 = 1200 (3000) - Max RPM, start slow!

// Step Input Multiplier
P98 = 20 Puls Multiplikator

P109 = 1 smoothing, 1=fixed smoothing, 2=s-Shaped smoothing
P110 = 30 Smoothing Filter Time 

P113 = 20% Feedforward
P114 = 10  Feedforward Fitler Time

P115 = 100% (100) - Gain
