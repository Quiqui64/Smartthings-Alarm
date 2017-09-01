# Smartthings-Alarm

Special thanks to a Smartthings forum regular Daniel Ogorchock and 

Cation when connecting the ESP8266 to the alarm keypad bus. Keypad bus uses 12V logic and the esp8266 uses 3.3V logic you need to use a voltage divider circuit or as I did a logic level converter https://www.sparkfun.com/products/12009
The original Arduino code came from these sources
http://www.avrfreaks.net/comment/804380#comment-804380 and https://github.com/emcniece/Arduino-Keybus

I tried to use this code but could not get it to work on the esp8266, I believe the problem has something to do with the ISR needs to be loaded into the esp8266 iram.

const char* ssid = "XXXXXXXXXX"; // your router login name
const char* password = "XXXXXXXXX"; // your router password


