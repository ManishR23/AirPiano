The Arduino Air Piano uses an ultrasonic sensor to detect the distance of your hand from the sensor. The sensor data triggers a corresponding tone on the buzzer and lights up one of three LEDs (Red, Yellow, Green), representing different musical notes based on distance. This project is a fun and simple way to combine electronics, programming, and music!


The ultrasonic sensor measures the distance between your hand and the sensor.
Based on the distance (in cm), different tones are played using the buzzer:
The LEDs provide visual feedback corresponding to the different distance ranges.

Testing and Troubleshooting:    
LEDs not lighting up: Ensure you have correctly connected each LED with a 220Ω resistor to the appropriate Arduino pin.
Buzzer not playing tones: Check the buzzer's connection to the correct pin and test it with a simple tone program.
Ultrasonic sensor not detecting distance: Verify the sensor’s wiring and orientation. The sensor should be pointed towards the area where your hand will be detected.

Additional Features
Modify the code to add more tones or play longer melodies as you move your hand in front of the sensor.
Adjust the distance ranges to suit your preferences for how far the sensor should detect the hand for each tone.

License
This project is open-source. You can freely use, modify, and distribute it under the terms of the MIT License.
