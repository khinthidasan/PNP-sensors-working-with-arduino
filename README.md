# PNP-sensors-working-with-arduino

Objective: Object detection


The main challenge:
PNP sensor is 24Voltages supply and Arduino works properly between 7 to 12Voltages. 

To overcome : 
Voltage Divider with Two resistors (R1 10kiloOhm , R2 7kiloOhm) is made to reduce sensor output 24V into arduino compatable voltage 


Sensor Type : PNP

Sensor : Sick Photoelectric sensor GL6-P1111 PNP

Cable Output: THREE cables (Brown +, Blue - and Black output)


Sensor Output : 
The output is the voltage between 24V or Zero.
The output becomes 24V with 1023 analog signal when the sensor receives the reflection from the refector. 
The output becomes 0V with 0 or random number analog signal when there is an obsacle between the sensor and the refector.
