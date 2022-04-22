# OBJECTIVE OF THIS PROJECT:
## Introduction:
The heat control system is basically used to control the temperature of a car seat. When a user or driver of the car gets seated on a car, the button sensor gets activated. After that, the user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the control system are done on a microcontroller called Atmega328.

## COMPONENTS AND SUPPLIES:
* Atmega328p
* LED bulb
* Connecting Wires
* Resistors
* 5V Voltage
* Switches
* Temperature sensor
* Potentiometer
* CRO
* Ram table
* Serial monitor

## Defining Our System
### Functionality
* When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
* Next the analog input from the temperature sensor is received and digitized.
* The digitized temperature input is visualized using Pulse Width Modulation.
* The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.


## HIGH LEVEL REQUIREMENTS:
|  ID    |                 Description                   | Status |
|  ---   | ---------------------------------------------  | ------- |
| HR01  |  LED glows indicating the actuation of the system and the heater | `Implementated` |
| HR02  | The analog input from the temperature sensor is received and digitized. | `Implementated` |
| HR03  | The digitized temperature input is visualized using Pulse Width Modulation | `Implementated` |
| HR04  | The data is displayed on the serial monitor | `Implementated` |
| HR05  | The digitized temperature input is transmitted by the UART protocol | `Implementated` |

## LOW LEVEL REQUIREMENTS:
|  ID    |                 Description                   | Status(Implementated/Future)  |
|  ---   | --------------------------------------------- |  --------------------------- |
| LR01  | Switches are closed, the first LED glows  | `Implementated` |
| LR02  | Led buld interfacing | `Implementated` |
| LR03  | Temperature sensor with Atmega328p | `Implementated` |
| LR04  | Temperature control measure and increase display | `Implementated` |
| LR05  | Oscilloscope visualization using Pulse width modulation | `Implementated` |

## BLOCK DIAGRAM:
![BlockDiagram](https://user-images.githubusercontent.com/102242702/164683027-a67a16d0-cb96-41e2-a0f3-a8f1df52ea4d.PNG)
  ### Data Flow line transistion:
  ![Flowline](https://user-images.githubusercontent.com/102242702/164683176-44d8b1d6-f333-40e5-9c64-f9a6760ce61c.PNG)

## 4W's and 1'H
## Who
*   People who drivers a lot in winter season can make use of these heat control system
## What
*   To bulid a system to heat seat at required temperature and monitoring the temperature accordingly

## When
*   When user wants to carry out the tasks quickly and this reduces manual work and saves time

## Where
*   This issue is in all parts cars where warming the seat and controlling the temperature

## How
*   By creating a system which will provide all the functionalities required, to turn on, automatic sensor activate, mornitoring temperature, maintaing required temperature

## * SWOT(ADVANTAGE,WEAKNESS,OPPORTUNITY,THREATS)
### ADVANTAGE:
* Activates automatic, warms the body in cold season and gives the appropriate results from temperature sensor.
* Gives an alter for person driving for an hours by over heat to take breake.

### WEAKNESS:
* LIMITED RANGE.

### OPPORTUNITY:
* INTERNET OF THINGS(IOT).
* In Autonomous vehicle field.

### THREATS:
* Sensor disconnection.
* Failure of components
* More Power consumption.

## OUTPUTS:
### OFF CONDITION

![Simulation_OFF](https://user-images.githubusercontent.com/102242702/164684699-8ab47f45-8d6a-4d07-a426-ef3b90cfac02.PNG)

### ON CONDITION

![Simulation_ON](https://user-images.githubusercontent.com/102242702/164684764-4cc9b292-79de-4584-ae5b-d25e06bdd444.PNG)
