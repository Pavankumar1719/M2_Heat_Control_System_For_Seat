# OBJECTIVE OF THIS PROJECT:
## Introduction:
The heat control system is basically used to control the temperature of a car seat. When a user or driver of the car gets seated on a car, the button sensor gets activated. After that, the user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the control system are done on a microcontroller called Atmega328.

## COMPONENTS AND SUPPLIES:
* Atmega328p
* LED bulb
* Connecting Wires
* Resistors
* 5V Voltage
* Switch
* Temperature sensor
* Potentiometer

## Defining Our System
### Explanation
*   #### Heat control system for seat have few features like automatic button sensor which will be activated, heater will be accessed, temperature sensore keeps monitoring the temperature and the analog values are sent to microcontroller called Atmega328p.

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

## ADVANTAGES:
* Activates automatic, warms the body in cold season and gives the appropriate results from temperature sensor.
* Gives an alter for person driving for an hours by over heat to take breake.

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
