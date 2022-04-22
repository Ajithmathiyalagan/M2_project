## Sample Test Cases
The control wire is used to communicate the angle. The angle is determined by the duration of a pulse that is applied to the control wire. This is called Pulse Coded Modulation. By changing the pot’s NOP position, servo motor will change its angle.

|pulse	|expected output	|passed or Not|
|Motor turned to 90 degree|	neutral position |	passed|
|Pulse is <1.5 ms|	Shaft turns closer to 0 degrees|	passed|
|Pulse is >1.5 ms|	Shaft turns closer to 180 Degrees|	passed|
