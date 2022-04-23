# M2_Heat_Control_System_For_Seat
## HEAT CONTROL SYSTEM

## Introduction
The heat control system is basically used to control the temperature of a car seat. When a user or driver of the car gets seated on a car, the button sensor gets activated. After that, the user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the control system are done on a microcontroller called Atmega328.

## Simulation
The functionality of the heat control system is coded in embedded c and the working is demonstrated using simuation in a software called SimulIDE. Below shows two images where in the 1st image shows the status of the simulation when the system is OFF and the second image shows the status of the system when it is ON.

## Functionality
*   When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
*   Next the analog input from the temperature sensor is received and digitized.
*   The digitized temperature input is visualized using Pulse Width Modulation.
*   The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.

## Output 
| Circuit | CRO |
| ------- | --- |
| ![Circuit](https://user-images.githubusercontent.com/102242702/164703827-a6db5379-84ba-4357-a87e-b96d68c55455.gif) | ![Oscilloscope](https://user-images.githubusercontent.com/102242702/164703922-4fbf591b-320b-4735-b4f6-c977bc124dfd.gif) |
| Ram Table | Serial Monitor |
| ![RAM_Table](https://user-images.githubusercontent.com/102242702/164704139-a981c7ec-a0c6-4a75-92e9-b069ed857420.gif) | ![Serial_Monitor](https://user-images.githubusercontent.com/102242702/164704210-e7d2b15f-21a2-4c83-bbc4-919254c93a6a.gif) |

## Simulation Output
![Simulation_ON](https://user-images.githubusercontent.com/102242702/164704832-2f2c3807-2a8a-4e1e-82fc-ed0acda7d400.PNG)
