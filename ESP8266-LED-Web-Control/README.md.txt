# ESP8266 LED Web Control 🔌💡

A professional single-page web interface to control an LED using ESP8266 over Wi-Fi.

## Features
- Dark professional UI
- Circular ON/OFF buttons
- No page reload (AJAX)
- Mobile friendly
- Auto Wi-Fi reconnect

## Hardware Required
- ESP8266 (NodeMCU / ESP-12)
- LED
- 220Ω resistor
- Jumper wires

## Circuit Connection
ESP8266 D1 (GPIO5) → 220Ω → LED → GND

## How It Works
- ESP8266 connects to your Wi-Fi
- Hosts a local web server
- Phone/Laptop opens ESP IP address
- Buttons send commands to ESP
- ESP controls LED

## Uploading Code
1. Open Arduino IDE
2. Select ESP8266 board
3. Upload `ESP8266_LED_Web_Control.ino`
4. Open Serial Monitor to get IP

## Author
Sayem 
