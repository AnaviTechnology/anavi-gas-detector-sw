# ANAVI Gas Detector Default Arduino Sketch

Open source Arduino sketch for the smart WiFi dev board ANAVI Gas Detector for [MQ gas sensors](https://playground.arduino.cc/Main/MQGasSensors/).

ANAVI Gas Detector is an open source, easy-to-use, Wi-Fi compatible development board for monitoring air quality and detecting dangerous gases. It supports popular analog MQ gas sensor modules such as MQ-135, MQ-2, MQ-3, etc. Furthermore, it comes with slots for mini OLED display and up to three additional I²C sensor modules, including the precise digital sensor HTU21D for measuring temperature and humidity.

Air pollution is a very serious problem. Monitoring air quality and detecting toxic gases can improve one’s quality of life. All these features make ANAVI Gas Detector appropriate for developers, makers, students and open source enthusiasts who are interested in home automation and an environmentally friendly lifestyle.

# User's Manual

[ANAVI Gas Detector User's Manual](https://github.com/AnaviTechnology/anavi-docs/blob/master/anavi-gas-detector/anavi-gas-detector.md)

# Dependencies

The default firmware of ANAVI Gas Detector depends on the following Arduino libraries:

* [WiFiManager by tzapu](https://github.com/tzapu/WiFiManager) (version 0.15.0)
* [ArduinoJson by Benoit Blanchon](https://arduinojson.org/) (version 6.11.2)
* [PubSubClient by Nick O'Leary](https://pubsubclient.knolleary.net/) (version 2.7.0)
* [Adafruit HTU21DF Library by Adafruit](https://github.com/adafruit/Adafruit_HTU21DF_Library) (version 1.0.1)
* [Adafruit APDS9960 Library by Adafruit](https://github.com/adafruit/Adafruit_APDS9960) (version 1.0.5)
* [DHT sensor library by Adafruit](https://github.com/adafruit/DHT-sensor-library) (version 1.3.4)
* [U8g2 by oliver](https://github.com/olikraus/u8g2) (version 2.23.18)
* [OneWire](https://github.com/PaulStoffregen/OneWire) (version 2.3.4)
* [DallasTemperature](https://github.com/milesburton/Arduino-Temperature-Control-Library) (version 3.8.0)
* [Adafruit Unified Sensor by Adafruit](https://github.com/adafruit/Adafruit_Sensor) (version 1.0.2)
* [Adafruit BMP085 Unified](https://github.com/adafruit/Adafruit_BMP085_Unified) (version 1.0.0)
* [NTPClient by Fabrice Weinberg](https://github.com/arduino-libraries/NTPClient) (version 3.1.0)
