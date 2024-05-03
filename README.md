# Engineering Interactive Technologies Project: Finger Tracking Kaleidoscope

This project uses MediaPipe to access your webcam and get the position of the tip of your pointer finger. This position gets translated to a canvas in Processing and draws the path of the tip of your pointer finger and mirrors it over multiple quadrants to encapsulate a kaleidoscope painting experience. A sensor attached to your wrist/hand tracks changes in tilt, which change the colors of your painting in real time, and another sensor that you tap clears the canvas.


How to run:
1. Connect two Arduinos to your device: one should be connected to a light sensor, the other should be connected to an IMU that is attached to your hand or wrist 
2. Upload the two Arduino files to the respective ports where the two Arduinos are connected
3. Modify the Processing port to set myPort1 to the port with your light sensor and myPort2 to the port with your IMU, then run the Processing file
4. Run the Python file

