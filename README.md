Smart_Irrigation_System_using_Arduino

This is a smart irrigation system in which we use soil moisture sensors with Arduino.
By gauging soil moisture levels, this irrigation system intelligently determines watering requirements before triggering the water pump via a relay module. Its automated functionality eliminates the need for manual oversight, ensuring seamless operation without intervention. We'll outline the intricate workings of this project for comprehensive understanding.

How does smart irrigation work?
We are using two soil moisture sensors that can sense the moisture content of the soil and send the output data to the Arduino. Place the soil moisture sensors in the soil. If the soil is dry that means the plants need some water so the sensor sends the signals to the Arduino. The Arduino sends the signals to the relay module and the water pump is turned on for some time. You can change the time by modifying the code. If all the water from the water pump will stay in a specific position/place then there is a chance that crops may destroy. To overcome this problem we are using a servo motor that can rotate the pipe from one position to other in a loop.

Smart irrigation system Components required:-
1.Arduino Uno
2.Servo motor
3.Soil moisture sensor
4.mini water pump
5.jumper wires.
6.Relay module
7.Breadboard

Circuit Diagram for smart irrigation system:-
![Image](https://github.com/Vignesh830/Smart_Irrigation_System_using_Arduino/assets/159744719/7fe8c82f-5146-494c-b599-f6c13d006a9f)

This is the circuit diagram for this project. Make the connections according to this diagram.

