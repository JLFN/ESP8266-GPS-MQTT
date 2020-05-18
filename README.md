# ESP8266-GPS-MQTT
Esp8266 with gps module send json mqtt 

1.Connect the VCC pin of the GPS module to the ESP32 3.3V pin.

2.Connect the GPS ground pin to the ESP32 ground pin.

3.Now, connect the RX pin of the GPS module to the TX pin of the ESP8266

connect the TX=D1 and RX=D2 (RX and TX pins of the ESP8266 are defined in the software).

4.Last, connect your ESP8266 to the computer through a USB cable. The ESP8266 will be powered from the USB 5V.

# Libs
WiFiClient

PubSubClient

TinyGPSPlus

SoftwareSerial
# Hardware
Esp8266 lolin D1 R2 Mini and Ublox Gps module
## TODO LIST
LWT and SSID strenght
