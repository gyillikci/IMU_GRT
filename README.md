# IMU_GRT
Processing and Arduino code for interfacing sensor data to Gesture Recognition Toolkit (GRT)

This is an interface code for transferring sensor data from Arduino to GRT GUI over Processing application. 
This interface derived from http://www.nickgillian.com/wiki/pmwiki.php/GRT/GUIProcessing and https://github.com/sebnil/RealtimePlotter

Arduino code:
It generates mockup data and prints data through serial port.

Processing code:

It listens Arduino's serial port. Received data from Arduino is sent to GRT GUI via UDP port.

NOTE: Make sure your port name is given correctly. You can check the port name by Arduino -> Tools -> Port.
Copy and paste the serial port address to the Processing code

To establish a connection:

-Load the Arduino code in to your Arduino
-Run the Processing code
-Start the GRT GUI
