# # Video 261: ESP32 Debugging with a cheap JTAG module  
Forget Serial.print statements, debug your code properly!  

![Thumbnail-00018 (Phone)](https://user-images.githubusercontent.com/20911308/223477128-8d5d9eb0-d804-4ba0-b9f6-d333689c8edf.png)

### Video link: https://youtu.be/lOG8-mQHZTw  
<br>  

[![JLCPCB Any colour including purple](https://user-images.githubusercontent.com/20911308/223475598-b2e00f51-f634-4802-a6c1-336b02c748d6.jpg "JLCPCB - $2 for 2, 4, 8-layer PCBs and more")](https://jlcpcb.com/)  

Rather than use a lot of Serial.print statements in your code, just connect up a cheap JTAG module from Espressif (the designers of the ESP32) to be able to step through your code a line at a time.

### Hardware  
► ESP-PROG (about $12 + shipping + taxes) https://s.click.aliexpress.com/e/_DFIm9RJ    
► Documentation #1: https://bit.ly/ESP32_Intro  
► Documentation #2: https://docs.platformio.org/en/latest/plus/debug-tools/esp-prog.html  
► Documentation #3: https://cdn.robotshop.com/media/s/spa/rb-spa-2030/pdf/esp-prog-datasheet.pdf  

► IDC adapter for 1.27mm IDC cable  
Adafruit: http://adafru.it/2743  

ESP32 MiniKit Debug Shield (for ESP32 Mini) by Brian Lough  
► https://store.eplop.co.uk/product/esp32-minikit-debug-shield/  

### Software  
► Driver for ESP-PROG using Zadig: https://zadig.akeo.ie/#  

### Essential reading, step-by-step!  
► ESP-Prog (Espressif): https://docs.platformio.org/en/latest/plus/debug-tools/esp-prog.html  
► How To Install: https://medium.com/@manuel.bl/low-cost-esp32-in-circuit-debugging-dbbee39e508b  
► How to Use: https://www.hackster.io/brian-lough/use-the-platformio-debugger-on-the-esp32-using-an-esp-prog-f633b6  
► More How To: https://www.visualmicro.com/page/ESP32-Debugging.aspx  

### Boards I've found to work reliably  
► ESP32 Mini T7 v1.3  
► TTGO ESP32 V1.8 / V1.7.1  
► Espressif ESP32 DevKit 1  
Basically, all the boards I own with a lidded "module" on them do not work. You get an error about being unable to get the memory maps.🤷  
This is unfortunate (for me) as I have many WROOM and WROVER modules!  

► List of all my videos
(Special thanks to Michael Kurt Vogel for compiling this)  
http://bit.ly/YouTubeVideoList-RalphBacon

► If you like this video please give it a thumbs up, share it and if you're not already subscribed please consider doing so and joining me on my Arduinite (and other μControllers) journey

My channel, GitHub and blog are here:  
\------------------------------------------------------------------  
• https://www.youtube.com/RalphBacon  
• https://ralphbacon.blog  
• https://github.com/RalphBacon  
• https://buymeacoffee.com/ralphbacon  
\------------------------------------------------------------------

My ABOUT page with email address: https://www.youtube.com/c/RalphBacon/about


