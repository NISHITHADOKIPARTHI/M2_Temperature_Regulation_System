### Requirements

## Introduction
Automobiles used in the cold regions must have seat heater along with the air-conditioning system. This ensures more comfort to the driver by adjusting the environment temperature close to nominal body temperature.

## Advantages
* Comfortable driving experience.
* Faster heating of seats and reduced dependancy of AC heater.
## Disadvantages
* Should be adjusted manually and cause distraction.
### SWOT Analysis
## Strength
* Ability to change temperature setting through the code
* Manual control of temperature adjustment
* Manual switching operation
* Limited temperature range
## Weakness
* No feedback loop to check temperature
* Fails to detect malfunction
## Opportunity
* To adapt with the AC environment settings
* To detect error if malfunctions
## Threat
* Excessive heating can damage the seat
### 4 W's and 1 H
## Who
* The driver and passengers.
## What
* Heated seats for more comfort.
## When
* Very effective during cold winters.
## Where
* In the seats of the automobile.
## How
* Heating system within the seat.

### HIGH LEVEL REQUIREMENTS

 | ID  |            Description                            |  Status         |
 |-----|---------------------------------------------------|-----------------|
 |HR01 |Supply PWM signals based on required temperature   | Implemented     |
 |HR02 |Should only be activated when driver seated        | Implemented     |
 |HR03 |Should be able to turn oFF manually                | Implemented     |

 ### LOW LEVEL REQUIREMENT

 | ID  |            Description                            |  Status         |
 |-----|---------------------------------------------------|-----------------|
 |LR01 |Specify the duty cycles based on temperature       | Implemented     |
 |LR02 |Reliability of the switch connected to seat        | Implemented     |
  

  