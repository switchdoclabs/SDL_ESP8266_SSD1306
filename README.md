SwitchDoc Labs SDL_ESP8266_SSD1306 Library

Library for SwitchDoc Labs Grove OLED 128x64
SwitchDoc Labs - www.switchdoc.com

Version 1.1 March 2016

http://www.switchdoc.com/

Note:   Some ESP8266 modules have pin 4 and 5 reversed.

If your display doesn't work, try changing:

In file SDL_ESP8266_SSD1306.cpp

    Wire.begin(4,5);

to

    Wire.begin(5,4);



