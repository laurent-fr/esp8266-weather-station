# ESP8266 Weather Station

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


