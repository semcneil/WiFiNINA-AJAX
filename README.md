# WiFiNINA AJAX Demonstration

 A simple web server that lets you blink an LED and read and ADC input
 without refreshing the page through AJAX.

 This sketch will print the IP address of your WiFi module (once connected)
 to the Serial Monitor. From there, you can open that address in a web browser
 to turn the LED on and off and read the ADC value.

 This example is written for a network using WPA encryption. For
 WEP or WPA, change the WiFi.begin() call accordingly.

 Circuit:
 * Board with NINA module (tested with an Arduino Nano Connect RP2040
 * LED_BUILTIN working
 * Analog source on A0
 
 Originally inspired by an AJAX interface for ESP32 at 
 https://circuits4you.com/2018/11/20/web-server-on-esp32-how-to-update-and-display-sensor-values/
