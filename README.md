# Final-graduation-Project
Electrical Water Heater Project

// Specifications–Temperature Setting
1. The “Up” or “Down” buttons are used to change the required water
temperature (set temperature).
3. The first “Up” or “Down” button press, enters the temperature setting mode.
4. After entering temperature setting mode, a single “Up” button press increase
the set temperature by 5 degrees.
5. After entering temperature setting mode, a single “Down” button press
decrease the set temperature by 5 degrees.
6. The minimum possible set temperature is 35 degrees.
7. The maximum possible set temperature is 75 degrees.
8. The “External E2PROM” should save the set temperature once set.
9. If the electric water heater is turned OFF then ON, the stored set temperature
should be retrieved from the “External E2PROM”.
10. The initial set temperature is 60 degrees.\\

// Specifications–ON/OFF Behavior
1. If power is connected to the heater, the electric water heater is in OFF state.
2. If the “ON/OFF” button is released and the electric water heater is in OFF state,
the electric water heater goes to ON state.
3. If the “ON/OFF” button is released and the electric water heater is in ON state,
the electric water heater goes to OFF state.
4. In the OFF state, all display should be turned OFF.\\

// Specifications–Temperature Sensing
1. The temperature sensor measures the water temperature.
2. The water temperature should increase, if the “Heating Element” is ON.
3. The water temperature should decrease, if the “Cooling Element” is ON.
4. T emperature should be sensed once every 100 ms.
5. The decision to turn ON or OFF either the “Heating Element” or the “Cooling
Element” based on the average of the last 10 temperature readings.

// Specifications–Heating/Cooling Elements
1. The “Heating Element” should be turned ON, if the current water temperature is less
than the set temperature by 5 degrees.
2. The “Cooling Element” should be turned OFF , if the current water temperature is less
than the set temperature by 5 degrees.
3. The “Heating Element” should be turned OFF , if the current water temperature is
greater than the set temperature by 5 degrees.
4. The “Cooling Element” should be turned ON, if the current water temperature is
greater than the set temperature by 5 degrees.\\


// Specifications–Seven Segments
1. Seven segment by default show the current water temperature or the set
temperature.
2. By default, the 2 seven segment display are show the current water
temperature.
3. If the electric water heater is in the temperature setting mode, the 2 seven
segment displays should blink every 1 second and show the set temperature.
4. In the temperature setting mode, every change in the set temperature should
be reflected on the 2 seven segment displays.
5. The 2 seven segment display should exit the temperature setting mode, if the
“UP” and “Down” buttons are not pressed for 5 seconds. \\

// Specifications–Heating Element Led
1. If the “Heating Element” is ON, the “Heating Element Led” should blink every 1
second.
2. If the “Cooling Element” is OB, the “Heating Element Led” should be ON.\\


// Components used

1. Internal EEPROM.
2. Temp sensor (LM35).
4. Heating Element (3d ceramic heater).
5. 7-segments.
6. LEDs.
7. Push Buttons.
8. Solid State Relays.
9. Cooling fins & fans.
\\ 
Drive link: 
https://drive.google.com/drive/folders/1Pbe6EMnI0DQZqXARCCOvfIm8QPqqnKSD?usp=sharing
