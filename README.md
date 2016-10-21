# CCS811 Breakout
This is a breakout board for the [CCS811] (http://www.ccmoss.com/gas-sensors#CCS811) (VOC/eCO2) gas sensor. All necessary pins for interfacing with the sensor are broken out. There is no external temperature and relative humidity sensor on the breakout and hence, the AUX pin is left floating. Temperature and relative humidity data from an external sensor can be manually written to ENV_DATA register (0x05) for dynamic compoensation.

Optional: Add 10K-ohm pull-ups on SDA and SCL when using with other devices on the bus.

Note: Arduino Library is currently under development.

<p align="center">
  <img src="https://github.com/AKstudios/CCS811-Breakout/blob/master/OSHPark%20render.png" alt="CRT Sensor Board"/>
</p>
