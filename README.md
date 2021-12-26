# **Obstacle Detection using Arduino and Ultrasonic Sensor**

## **Aim**
The aim of this project is 
- To detect any obstacle within a specified range
- To calculate the distance of the obstacle from the sensor

## **Working Principle**
The distance is calculated based on the time of flight of the ultrasonic wave i.e. distance is calculated based on the time elapsed between the emission of the wave and the reception of the echo.

 2D = T x C \
 D  = 1/2 x T x C
 

## **Components Required**
- Arduino UNO x 1
- Ultrasonic Sensor HC-SRO4 x 1
- Buzzzer Module (Piezo speaker) x 1
- LCD Display 
- Breadboard
- Jumper wires

## **Circuit Connections**
_Ultrasonic Sensor Connections_
- Vcc Pin ------> +5V
- Gnd Pin ------> Gnd
- Trig Pin -----> D10
- Echo Pin -----> D9

_Buzzer Connections_
- Positive Terminal ----> D2
- Negative Terminal ----> Gnd

_LCD Connections_
- Vcc Pin ----> +5V
- Gnd Pin ----> Gnd
- SCL Pin ----> A5 Pin
- SDA Pin ----> A4 Pin 








