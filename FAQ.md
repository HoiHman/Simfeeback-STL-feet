## Flashing the Arduino 
1. Open Simfeedback Application 
2. Navigate to Setup tab on top
3. Choose correct com port and click Datei auswählen
4. Browse to the hex file which you want flash (for example ACServo_Leonardo_00_07_05.hex) and press upload



=== Nothing moves after first installation or update of simfeedback ===
#Check Simfeedback.xml -> change value comPort to the correct Arduino comPort (check device manager)
 </MotorList>
      <comPort>1</comPort>
      <baudRate>460800</baudRate>
      <id>1</id>
      <type>4DC</type>
 </MotionControllerConfigData>

