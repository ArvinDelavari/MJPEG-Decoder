# MJPEG-Decoder
MJPEG Class for TFT LCDs Arduino/STM32/ESP32
- Compatible with Adafruit_GFX, Arduino_GFX and TFT_eSPI
- You can read .mjpeg files from SD card and display them on LCD
- Using MJPEG is more efficient than displaying frames in JPEG seperatly on TFT LCD
- Delay in in this decoding is reduced form 160/170ms in JPEG Decoder libraries to less than 80ms
- Oringinal JPEG Decoder : https://github.com/Bodmer/TJpg_Decoder
- include this .h file in the main code to use the class
