Adafruit I2C LCD Plate
======================

Node.js implementation for the Adafruit RGB 16x2 LCD+Keypad Kit for Raspberry Pi 
http://www.adafruit.com/products/1110



Usage
-----
```javascript
var LCDPLATE, lcd;
LCDPLATE = require('adafruit-i2c-lcd').plate;
lcd = new LCDPLATE('/dev/i2c-1', 0x20);
lcd.backlight = lcd.colors.red;
lcd.message('Hello World!');
lcd.init();
```
See the wiki for details on the functions and events.

## Licence
BSD

Based on the [Adafruit's Raspberry-Pi Python Code Library](https://github.com/adafruit/Adafruit-Raspberry-Pi-Python-Code.git)

>  Here is a growing collection of libraries and example python scripts
>  for controlling a variety of Adafruit electronics with a Raspberry Pi
  
>  In progress!
>
>  Adafruit invests time and resources providing this open source code,
>  please support Adafruit and open-source hardware by purchasing
>  products from Adafruit!
>
>  Written by Limor Fried, Kevin Townsend and Mikey Sklar for Adafruit Industries.
>  BSD license, all text above must be included in any redistribution
>
>  To download, we suggest logging into your Pi with Internet accessibility and typing:
>  git clone https://github.com/adafruit/Adafruit-Raspberry-Pi-Python-Code.git
