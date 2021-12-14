# Adaptive-Cruise-Control-with-Cloud-Connectivity
Software: Matlab, Hardware: Arduino UNO
# About Cruise Control and Adaptive Cruise Control Mode.  
Cruise Control and Adaptive Cruise Control are driver assistance systems for road 
vehicles to provide a better and safer driving experience. In the CC mode, the speed of 
the vehicle can be set to a constant desired speed. This provides a convenient method for 
drivers to travel on highways. In the ACC mode the speed of the vehicle is maintained at 
a constant desired speed as well as altered if obstacles are detected in front of the vehicle 
on the basis of the information obtained by several sensors that are mounted on the 
vehicle. The purpose of CC and ACC systems is to enhance the safety of people in the 
vehicle which is achieved by maintaining a safe distance from other vehicles as well as 
ensuring that the speed limit is not exceeded. Furthermore, it also contributes to a better 
driving experience.  

There are several types of cruise control systems that make use of different types of 
sensor systems such as Laser Based systems, Radar Based systems and many more. This 
project aims at developing an ACC system using the Arduino Uno board and MATLAB 
programming language. The distance sensing mechanism is achieved by using an 
ultrasonic sensor.  
# Project Requirements 
The Adaptive Cruise Control system makes use of the following hardware components: 

 Arduino Uno board  

 Ultrasonic distance sensor

 Liquid Crystal Display 

 Control buttons

 220 Ω resistor 

 10 KΩ Potentiometer

Along with the above mentioned components, MATLAB requires support packages for 
Arduino Hardware to program the microcontroller board.

# Functionalities 
The key functionalities of this cruise control system are as follows: 
1. The speed of the system can be increased or decreased using the increase and 
decrease buttons. 
2. The user can enter and exit the Cruise Control (CC) mode using the buttons. 
When the cruise control mode is enables using the set speed button, the system 
should hold the speed in that instant constant. Furthermore, this constant speed 
can be altered through the increase and decrease buttons. The user can exit the 
cruise control mode using the cancel button. 
3. The user can enter Adaptive Cruise Control mode by using the Adaptive speed 
button. This offers the same functionality as the Cruise Control mode with and 
additional feature where the speed of the ego vehicle is decreased when another 
vehicle is encountered in front via the ultrasonic sensor. In this way, a safe 
distance is maintained from other vehicles. Furthermore, to differentiate the ACC 
mode from CC mode the display will be programmed to blink constantly in the 
ACC mode. 
4. The speed data is analyzed on the cloud through ThingSpeak platform.

![image](https://user-images.githubusercontent.com/88471779/128289188-4b84b8a8-12cc-4dae-a1a5-2eb9517ce21a.png)
