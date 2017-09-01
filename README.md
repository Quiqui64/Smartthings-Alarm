# Smartthings-Alarm

Cation when connecting the ESP8266 to the alarm keypad bus. Keypad bus uses 12V logic and the esp8266 uses 3.3V logic you need to use a voltage divider circuit or as I did a logic level converter https://www.sparkfun.com/products/12009
The original Arduino code came from these sources
http://www.avrfreaks.net/comment/804380#comment-804380 and https://github.com/emcniece/Arduino-Keybus

const char* ssid = "XXXXXXXXXX"; // your router login name
const char* password = "XXXXXXXXX"; // your router password

