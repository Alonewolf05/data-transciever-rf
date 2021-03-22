# data-transciever-rf
Sensor Data Transciever Through RF

There are 4 parts in this board.
- Nucleo-32 Board
- BNO055 IMU
- nRF2401 RF Transciever
- Boost converter

Boost converter is for Li-Ion battery powered applications.
It boosts the voltage to the 10V and power the nucleo through Vin pin.
10V is choosen because Nucleo's ST-Link MCU works from Vin pin. **NOT 5V or 3.3V**

