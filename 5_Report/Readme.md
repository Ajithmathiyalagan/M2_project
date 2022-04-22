## Servo Motor angle Control With Distance
   Distance Measurement using Arduino Ultrasonic Sensor is a project to measure shorter distance precisely. Before getting started you must know about Ultrasonic Sensor HC SR-04, which is a low-cost sensor. The ultrasonic sensor is consists of Transmitter and Receiver modules. Transmitter part ejects the pulse out and the receiver part receives the pulse. If an obstacle is placed before the sensor, the transmitted pulse ejected strike the obstacle and reflected back. The reflected pulse is received by the receiver part. The time between transmission and reception is calculated. This data is processed to calculate distance
   ## Ultrasonic Sensor Module
The HC-SR04 is a long range ultrasonic sensor module for measuring the distance or we can also use it for detecting the objects. The range of the ultrasonic sensor is around 2cm to 400cm. The sensor module has an ultrasonic transmitter and receiver. Ultrasonic sensor working principle is similar to bats and dolphins.

A sensor module transmits ultrasound signal at 40 000 Hz and if there is any object in the path the signal bounce back to the module. It can be used as long distance measurement, range finder, and water level detector.

## Push Button
A push-button or simply button is a simple switch mechanism to control some aspect of a machine or a process. Buttons are typically made out of hard material, usually plastic or metal. The surface is usually flat or shaped to accommodate the human finger or hand, so as to be easily depressed or pushed. Buttons are most often biased switches, although many un-biased buttons still require a spring to return to their un-pushed state. Terms for the "pushing" of a button include pressing, depressing, mashing, slapping, hitting, and punching.

## Micro Servo Motor SG90
Micro Servo Motor SG90 is a tiny and lightweight server motor with high output power. Servo can rotate approximately 180 degrees (90 in each direction), and works just like the standard kinds but smaller. You can use any servo code, hardware or library to control these servos. Good for beginners who want to make stuff move without building a motor controller with feedback & gear box, especially

since it will fit in small places. It comes with a 3 horns (arms) and hardware.

## potentiometer
A potentiometer is an electronic device that measures the EMF (electromotive force) of a cell as well as the cell’s internal resistance. It’s also used to compare the EMFs of various cells. In most applications, it may also be used as a variable resistor. These potentiometers are widely employed in the production of electronics equipment that allows users to alter electrical circuits to achieve the desired outputs. Although its most obvious application must be for volume controls on radios and other audio-related electronic equipment.

## Lcd Modules
LCD modules form a very important in many Arduino based embedded system designs to improve the user interface of the system. Interfacing with Arduino gives the programmer more freedom to customise the code easily. Any Arduino board, a 16X2 LCD display, jumper wires and a breadboard are sufficient enough to build the circuit.

## High Level Requirements
| ID | Description | Category |	Status |
|:-: |:-----------:|:--------:|:------:|
| HRL01 | The high-level signal is sent to 10 microseconds using Trigger.| Technical | Implemented |
| HRL02 |he module sends 40 KHz signals automatically and then detects whether the pulse is received or not through Echo.| Technical | Implemented |
| HRL03 | If the signal is received, then it is through high level. The time of high duration is the time gap between sending and receiving the signal. | Technical | Implemented |
## Low Level Requirements
| ID | Description | HLR ID | Status (Implemented/Future) |
|:-:|:-----------:|:------:|:---------------------------:|
| LLR01 | Sensor output will be in the form of digital valuen in the LCD display' | HR01 | IMPLEMENTED |
| LLR02 | servo expects to see a pulse every 20 milliseconds (.02 seconds). | HR02 | IMPLEMENTED |
| LLR03 | We will make the motor turn to the 90-degree position (often called as the neutral position). | HR03 | IMPLEMENTED |
| LLR04 |If the pulse is shorter than 1.5 milliseconds, then the motor will turn the shaft closer to 0 degrees. | HR04 | IMPLEMENTED |
| LLR05 |If the pulse is longer than 1.5 milliseconds, the shaft turns closer to 180 degrees.  | HR05 | IMPLEMENTED |