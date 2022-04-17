![Flite](https://github.com/DJMarlow/Flite/blob/master/logo_raw.png)

**Flite Sensor Arduino Library**
----

This is a fork of DJMarlow's original flite sensor arduino library, with the (as yet unrealized) intent of providing support several alternative temperature sensors.
The recommended HSCMAND150PA4A3 temp/pressure sensor is quite expensive, and pressure sensing and has limited utility for many users, so this fork will attempt to add support for the following i2c temperature sensors using the same wiring configuration:

- HTU21D Temperature and Humidity Sensor (Humidity not used)
- LM75 Temperature Sensor
- MLX90614 Infrared Sensor (using through-hole for pressure sensor)
- MLX90615 Infrared Sensor (using through-hole for pressure sensor)

(A fork to the flite controller code will hopefully allow storage of the sensor configuration in CMOS

[Arduino Library Documentation](https://gist.github.com/DJMarlow/8b56c0b791cbcbb7c4312fbd56bc55f3)

Depends upon the [Adafruit VL53L0X library](https://github.com/adafruit/Adafruit_VL53L0X).  Be sure to include that in your project.
