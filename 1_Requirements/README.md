# Requirements

## Introduction 

The heat control system is basically used to control the temperature of a car seat. When a user or driver of the car gets seated on a car, the button sensor gets activated. After that, the user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the control system are done on a microcontroller called Atmega328.

## Research

In the past few years, the need for automation has increased and has been widely applied for measuring heating systems. There are plenty of commercial temperature control systems which can be bought from manufacturers or from inventors, and also, quite a lot of work have been published in this area. Our work is similar to the work it measure value as a persons seatimg for an hours and driving based on that temperature measure diplayed in oscilloscope, the control measure has been implementated in variour methods like ventilator seat to overcome the heat of seat. But it differs in the sense that, our work take into account, the ease of programming the microcontroller and user-friendliness by using keypad to enter a reference value.

## Features

*   ### Measuring seat temperature
*   ### Control feature for heat
*   ### Helps in winter season to keep warm

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

## Low Level-Requirement  
|  ID    |                 Description                   |  HLR ID  | Status(Implementated/Future)  |
|  ---   | --------------------------------------------- | -------- | ----------------------------- |
| LR01  | User shall be able to login to the system with correct login details  | HR01  | `Implementated` |
| LR02  | User need to book a ticket in a user entry mode | HR01  | `Implementated` |
| LR03  | If appropriate login details are not entered a message is displayed "Wrong password" | HR01  | `Implementated` |
| LR04  | Displaying the movies available | HR02  | `Implementated` |
| LR05  | Admin can change the price for the movie | HR02  | `Implementated` |
| LR06  | If user specifies seat number which is booked, message appears that the seat is unavailable | HR03  | `Implementated` |
| LR07  | Displaying the summary of the ticket booked | HR03  | `Implementated` |

## High Level-Requiements
|  ID    |                 Description                   |  Category  | Status |
|  ---   | --------------------------------------------- | -------- | ----------------------------- |
| LR01  | User shall be able to login the system  | Technical | `Implementated` |
| LR02  | User shall be able to purchase a ticket | Technical | `Implementated` |
| LR03  | User shall be able to get summary of the ticket booked | Technical | `Implementated` |
| LR04  | User shall be able to cancel a ticket | Technical | `Implementated` |
| LR05  | User shall be able to view the reserved seats | Technical | `Implementated` |


