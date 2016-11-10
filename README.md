# CCS811 Breakout
This is a breakout board for the [CCS811] (http://www.ccmoss.com/gas-sensors#CCS811) (VOC/eCO2) gas sensor by [AMS] (http://ams.com/eng/Products/Environmental-Sensors/Gas-Sensors/CCS811). All necessary pins for interfacing with the sensor are broken out. There is no external temperature and relative humidity sensor on the breakout and hence, the AUX pin is left floating. Temperature and relative humidity data from an external sensor can be manually written to ENV_DATA register (0x05) for dynamic compensation.Optionally, you can add 10K-ohm pull-ups on SDA and SCL when using with other devices on the bus.

Note: After reflow, allow 24-48 hours of burn-in time before the sensor starts reporting any good readings.

Arduino library available [here] (https://github.com/AKstudios/CCS811-library).

<p align="center">
  <img src="https://github.com/AKstudios/CCS811-Breakout/blob/master/OSHPark%20render.png" alt="CRT Sensor Board"/>
</p>

<p align="center"><a href="https://oshpark.com/shared_projects/Z87HMosP"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a></p>
