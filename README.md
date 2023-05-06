# BHARAT-Intern_Project
1. Smart Parking System using Arduino Uno :-
There are two parking slots in our project. If you want to increase the number of paring slots then add a few more IR sensors and modify the code accordingly.
The system automatically detects whether the parking slot is empty or not. If the slot is empty in the automated car parking the new vehicles are allowed to enter else the entrance is blocked by the servo barrier in case the parking is full.
The visitors can see the status for the availability of the free space outside the parking on a 16×2 LCD. They can also see on the LCD how many parking slots are free. The data keeps updating as the vehicles move in and out of the parking.

Components Required
Arduino UNO
Two IR sensors
Servo motor
16×2 LCD
USB cable for uploading the code

automatic car parking Circuit Diagramis below
automatic car parkingBefore starting please check the address of the I2C module that you are using and modify the code accordingly.

Then connect the 5 volts pin of the Arduino with the VCC pin of the I2C module, the red wire of the servo motor, and the VCC pin of both the IR sensors.
Join the SDA pin of the I2C module with the analog-4 pin of the Arduino and the SCL pin of the I2C module with the analog-5 pin of the Arduino in this automatic car parking system project.Connect the GND pin of the Arduino with the GND pin of the I2C module, the brown wire of the servo motor, and the GND pin of both the IR sensors. Attach the orange(signal) wire of the servo motor to the digital-9 pin of the Arduino.

Now connect the pins of the I2C module with the pins of 16×2 LCD.
You can check here the interfacing of 16×2 LCD with the I2C module. At last, connect the OUT pin of the first IR sensor with the digital-4 pin of the Arduino and the OUT pin of the second IR sensor with the digital-7 pin of the Arduino.
