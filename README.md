WeatherSensorClient
===================
This is an Arduino sketch which monitors multiple weather sensors 
and uploads observations to a SmartObject API server using HTTP PUT 
operations over ethernet.

The sensors are:

Wind speed, wind direction, rainfall:
SparkFun Weather Sensor part # SEN-08942
https://www.sparkfun.com/products/8942

Indoor Humidity:
SparkFun HIH-4030 breakout board, part # SEN-09569
https://www.sparkfun.com/products/9569

Barometric Pressure, indoor temperature:
SparkFun BMP085 breakout board, part # SEN-11282
https://www.sparkfun.com/products/11282

Outdoor Humidity and Temperature:
SparkFun SHT15 breakout board, part # SEN-08257
https://www.sparkfun.com/products/8257

