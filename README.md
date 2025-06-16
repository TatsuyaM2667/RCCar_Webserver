# RCCar_Webserver
このコードはESP32でDNSサーバーをたて、ウェブサイトからL298nを使用して二つのモーターを制御する仕組みとなっている。

配線は以下の通り

|ESP32(Deckit-C) |  L298n      | 
|:---------------|------------:|
| 5V             | 5V          |   
| GND            | GND         |
| GPIO27         | IN1         |
| GPIO26         | IN2         |
| GPIO14         | EN1         |
| GPIO33         | IN3         |  
| GPIO25         | IN4         |  
| GPIO32         | EN2         |  


