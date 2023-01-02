# ESP32-C3FH4-RGB 

![image](https://github.com/andypiper/fivebyfive/blob/main/reference/ESP32-C3FH4-RGB-reference.jpeg)


![image](https://github.com/ccattuto/wordle-device/blob/main/wordle-device.jpg)

# driver

https://zadig.akeo.ie/


# General Flashing Instructions:

Install driver with zadig as mentioned above.
Install Arduino IDE and install espressif resources by adding line "https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json" to Additional Boards Manager URLs in Arduino IDE Files / Preferences.
Via Arduino IDE Tools/Board / Board Manager search for ESP32 and choose the latest spressif Systems version to install it.
Install ESP32 Digital RGB LED Drivers and Adafruit NeoPixel via option tools / Manage Libraries in Arduino IDE.

Setup connection to connect to Board ESP32C3 Dev Module and to enable serial connection to the board, set USB CDC On Boot to Enabled and set JTAG Adaptor to ESP USB Serial as well as selecting the correct com port

![image](https://user-images.githubusercontent.com/2357428/210257877-296f6293-aa9b-45fe-b452-021c4390347a.png)


Other settings see settings.png.

# Upload sketch from Arduino IDE:

Hold down B button on board, press R button and release again but keep on pressing B, trigger Arduino IDE to upload sketch, keep B pressed until Arduino IDE says that it's connected. Then you can release B button.

Serial works with "CDC enable on boot" set to true.

# Other branches

fivebyfive-by Andy piper
https://github.com/andypiper/fivebyfive

wordle-device-Ciro Cattuto
https://github.com/ccattuto/wordle-device

# esp32c3-bling Series' Articles

https://dev.to/andypiper/series/16659

https://bigl.es/friday-fun-micro-weather-station/

# Open Source / Contributors


Andy piper (for fivebyfive),

biglesp (Micro Weather Station),

Ciro Cattuto (for wordle-device),

Geek Mom Projects([Sites Using React](https://twitter.com/GeekMomProjects/status/1479210241807900676)  ),

And many many others who haven't been mentioned....

# Contact 01Space
facebook:Jiale Xu
twitter:yongxiangxu251
E-mail：759315223@qq.com
