# Temperature-sensor-FPGA
The project involves the temperature sensor DS18B20 and FPGA BASYS3.
The temp sensor measures temperatures from -55C to 125C.

Tools-
1. Basys3
2. Arduino uno
3. Temperature sensor DS18B20
4. Buzzer
5. Leds (1 red and 1 blue)
6. Keypad
7. wires
8. Breadboard
9. 3 cups

Software-
1. Vivado- VHDL
2. Arduino
   
The project-

In this project, three cups are used, each containing:
1.	Hot water
2.	Room temperature water
3.	Ice

   
As we measured the temperature of the water in each cup, the FPGA board displayed the corresponding temperature. The different modes are utilized of the system to test the sensor in each cup, allowing us to observe all the functionalities.
•	Mode 1 (Checking if the temperature is over 50°C): When in this mode, the buzzer and the red LED successfully activate when the temperature exceeds 50°C.
•	Mode 2 (Checking if the temperature is under 10°C): In this mode, the buzzer and the blue LED turn on when the temperature falls below 10°C.
•	Mode 3 (Checking if the temperature is over the user-defined threshold): The buzzer and the red LED are triggered when the temperature exceeds the threshold set by the user via the keypad.
•	Mode 4 (Checking if the temperature is under the user-defined threshold): The buzzer and the blue LED activate when the temperature is below the user-defined threshold.
Throughout all modes, the temperature is continuously displayed on the FPGA board.
This testing process effectively demonstrates the system's ability to handle varying temperature conditions and accurately display the temperature while engaging the appropriate alerts based on user-defined thresholds.


Links to the videos in Youtube-

  https://www.youtube.com/watch?v=Jwe6oWMPyZE&list=PLejz4G5i2PCac-pyeZiZoc6fPHPi7-JGv&index=2
  
  https://www.youtube.com/watch?v=TRDaP4a6h9g&list=PLejz4G5i2PCac-pyeZiZoc6fPHPi7-JGv&index=1
  
![system2](https://github.com/yaelkeidar/Temp-sensor-FPGA/assets/154610976/3cc4338d-852f-42ce-ad0f-4aca118c1afa)
