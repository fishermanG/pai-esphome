# pai-esphome
Using ESPHome to interface between your Paradox Alarm unit with Home Assistant

Monitor your zones, arm/disarm, allow panic trigger.

## Equipments:
1) Paradox SP5500
2) USB Buck DC-DC Converter 12v-5v (I powered using a USB cable but you could wire up the output of the buck converter directly to VIN and GND)
3) ESP8266
4) 1 channel 5v/3.3v Relay Module

## Softwares:
1) ESPHome
2) MQTT Client
3) PAI (https://github.com/ParadoxAlarmInterface/pai)

## Connection diagram:
![alt text](https://user-images.githubusercontent.com/24431798/135411875-487e2682-08b4-46db-a6df-eac59bdb2f83.jpg)

You can use ESP32 as well (tested)

For more information, please visit https://github.com/ParadoxAlarmInterface/pai

## Thanks
- Oxan & Bojan - https://github.com/oxan/esphome-stream-server - For making UART Stream over WiFi possible in ESPHome
