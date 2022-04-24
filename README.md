# M2_Temperature_Regulation_System
CodeInspector:
Codiga - Static Analysis ![Codiga Badge](https://api.codiga.io/project/32875/score/svg)

Codiga grade [![Code Grade](https://api.codiga.io/project/33041/status/svg)]

Codacy Badge [![Codacy Badge](https://app.codacy.com/project/badge/Grade/173b8257e5364b8f9f48da2135b63b73)](https://www.codacy.com/gh/NISHITHADOKIPARTHI/M2_Temperature_Regulation_System/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=NISHITHADOKIPARTHI/M2_Temperature_Regulation_System&amp;utm_campaign=Badge_Grade)

## Introduction
The Temperature Regulation system is basically used to control the temperature of a car seat. When a passanger or a driver of the car seats on a car, the button sensor gets activated (which acts as one switch here). After that, the user can turn on the heater(which acts as another switch). The temperature sensor keeps monitoring and recording the temperature and sends the analog value to the microcontroller ATmega328. The microcontroller takes the analog input of the temperature sensor and gives output a temperature value through UART( through serial communication).
The system is used to warm the seates of automobiles when used in cold freezing winters.

## Input and connections
* Seat switch (D0)
* Heat switch (D1)
* Heat adjust potentiometer (C0)

## Output
* Heater LED (B0)
* heat-level indicator (B2 & B3)
* Oscilloscope (B1)

## Circuit
![All OFF](https://user-images.githubusercontent.com/89698000/133667355-08574e76-b4e7-4db2-b7f9-ebfd292bffb2.png)


