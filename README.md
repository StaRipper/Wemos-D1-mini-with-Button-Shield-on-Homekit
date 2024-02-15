# Wemos-D1-mini-with-Button-Shield-on-Homekit

Wemos D1 mini with Button Shield on Apple HomeKit as Stateless Programmable Button.

Instructions:

1. Solder the Button Shield to the Wemos D1 Mini board (Used Pins are: D3, GND, 3v3).
2. Install Arduino IDE software (Can be installed from Microsoft Store).
3. Using Arduino IDE software update file wifi_info.h with your WiFi ssid and password.
4. The HomeKit pairing code is 111-11-111 (It can be changed in my_accessory.c file).
5. Using Arduino IDE software compile and flash the Wemos D1 Mini via USB cable.
6. Open Home App in your Apple device and (+) add accessory --> more options --> A "Stateless Programmable Switch" will be available --> enter code.
7. The button can be configured in Apple Home App (see picture).
8. Thats it. Enjoy.  

![image](https://github.com/StaRipper/Wemos-D1-mini-with-Button-Shield-on-Homekit/assets/22976153/34d2d08e-b1c6-4694-99aa-bc12b6fb1bda)


![image](https://github.com/StaRipper/Wemos-D1-mini-with-Button-Shield-on-Homekit/assets/22976153/2871f31a-4c53-4d8c-91a7-d4a618add1ab)


Boards used:

Button Shield: https://www.wemos.cc/en/latest/d1_mini_shield/1_button.html

Wemos D1 mini: https://www.wemos.cc/en/latest/d1/d1_mini.html
