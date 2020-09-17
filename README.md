# PNP-sensors-working-with-arduino

Objective: Object detection


The main challenge:
PNP sensor is 24Voltages supply and Arduino works properly between 7 to 12Voltages. 

To overcome : 
Voltage Divider with Two resistors (R1 10kiloOhm , R2 7kiloOhm)


Sensor Type : PNP
Sensor : Sick Photoelectric sensor GL6-P1111 PNP
Cable Output: THREE cables (Brown +, Blue - and Black output)
Sensor Output : 
Output is the voltage between 24V or Zero
When the sensor receives the reflection from the refector, the output becomes 24V with 1023 analog signal
When there is an obsacle between the sensor and the refector, the output becomes 0V with 0 or random number analog signal
