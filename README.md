# Aku-Bento (Evil Lunch Box)
悪弁当(Aku bentō) is a project for a lunch box that contains an ESP32 & an ESP8266 used for beacon flooding

## Materials required <br>
* DOIT ESP32 DEVKIT V1 or any generic ESP32<br>
* WEMOS D1 R1 (ESP8266) or any generic ESP8266<br>
* A $2 plastic lunch box <br>

## Connection Diagram <br>
<img src="Assets/circuit diagram.png" width="700dp">

## Pin Connections <br>
ESP32 &nbsp; ----> ESP8266 <br>
VIN &nbsp; &nbsp; &nbsp; ----> 5V <br>
GND &nbsp; &nbsp; ----> GND <br>
GPIO13 ----> D7 <br>

## Instructions <br>
1. Flash your ESP32 with ESP32_CODE.ino using Arduino IDE
2. Flash your ESP8266 with ESP8266_CODE.ino using Arduino IDE
3. Connect the pins according to the Pin Connections above
4. Use a BLE scanner and send text "HIGH" to activate the spammer and any other value to deactivate it

## Disclaimer  
Even if it is more of a fun party trick than something that could actually do any harm, please use it respectfully! Some people might interpret this as a "Jammer" and those are illegal. But this project is just sending a bunch of WiFi packets through the air and works within the 802.11 Wi-Fi standard.

## Sources
* <a href="https://github.com/nkolban/ESP32_BLE_Arduino/blob/master/examples/BLE_write/BLE_write.ino">ESP32 BLE GATT SERVER</a><br>
* <a href="https://github.com/spacehuhn/esp8266_beaconSpam">ESP8266 WiFi Beacon Spam</a>

## Languages used<br>
* C++
