# Wemos-D1-mini-with-Button-Shield-on-Homekit

Wemos D1 mini with Button Shield on Apple HomeKit

Instaructions:
1. Solder the Button Shield to the Wemos D1 Mini board (Pin D3 is used by the button).
2. Install Arduino IDE software (Can be installed from Microsoft Store).
3. Using Arduino IDE software update file wifi_info.h with your WiFi ssid and password.
4. The HomeKit pairing code is 111-11-111 (It can be changed in my_accessory.c file).
5. Using Arduino IDE software compile and flash the Wemos D1 Mini.
6. Open Home App in your Apple device and (+) add accessory --> more options --> A "Stateless Programmable Switch" will be available --> enter code 111-11-111
7. Thats it. Enjoy.  

![image](https://github.com/StaRipper/Wemos-D1-mini-with-Button-Shield-on-Homekit/assets/22976153/34d2d08e-b1c6-4694-99aa-bc12b6fb1bda)
