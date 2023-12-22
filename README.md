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

Software-
1. Vivado- VHDL
2. Arduino
   
The project-
   While measuring the temp, the FPGA basys3 displays the temp.
sw1 - if the temp is over 50C, the buzzer starts working and the red led starts flashing.
sw2 - if the temp is under 10C, the buzzer starts working and the blue led starts flashing.
   * The system also works when both sw1 and sw2 are on.
sw3- The user can determine the hot temperature threshold by using the keypad.
  After determining the new hot temperature threshold, if the measured temperature is over from that temperature, the buzzer starts working and the red led starts flashing.
sw4- The user can determine the cold temperature threshold by using the keypad.
  After determining the new cold temperature threshold, if the measured temperature is under from that temperature, the buzzer starts working and the blue led starts flashing.
 * The system also works when both sw3 and sw4 are on.
