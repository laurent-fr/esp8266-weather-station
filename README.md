# ESP8266 Weather Station

## Hardware

Bill of Materials :
* 1x ESP8266-12
* 1x BME280 Board
* 1x TTL<->USB Board
* 5x 10K resistor
* 1x 3.3v Power Supply

![Schematic](/doc/schematic.jpg)

![Board](/doc/board.jpg)

## Software

Add the following library to the arduino IDE :
* https://github.com/sparkfun/SparkFun_BME280_Arduino_Library

If not already done, add ESP8266 support to the IDE : https://github.com/esp8266/Arduino

Before compiling, create a file named 'wifi.h' with your wifi settings :


```c
const char* ssid = "<SSID>";
const char* password = "<wifi password>";
```

You can see the IP address on the serial console.

On a web browser, you should see something like this :

    Temperature:    29.6 C
    Pression:     1011.8 Pa
    Altitude:      12.83 m
    Humidite:         40 %


