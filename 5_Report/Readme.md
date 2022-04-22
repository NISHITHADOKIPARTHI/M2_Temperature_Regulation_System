## TemperatureRegulationSystem


* The Temperature Regulation system is basically used to control the temperature of a car seat.
* When a passanger or a driver of the car seats on a car, the button sensor gets activated (which acts as one switch   here.
* After that, the user can turn on the heater(which acts as another switch).
* The temperature sensor keeps monitoring and recording the temperature and sends the analog value to the microcontroller ATmega328. 
 
  Temperature sensor works as :

        ADC Value (Temp Sensor)| Output PWM
        ----------|----------
            0-200 | 20% - 20 °C
          210-500 | 40% - 25 °C
           510-700 | 70% - 29 °C
          710-1024 | 95% - 33 °C

*  The microcontroller takes the analog input of the temperature sensor and gives output a temperature value through UART( through serial communication). 
 * The system is used to warm the seates of automobiles when used in cold freezing winters.