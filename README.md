# RCCar_Webserver
このコードはESP32でDNSサーバーをたて、ウェブサイトからL298nを使用して二つのモーターを制御する仕組みとなっている。
## 必要なもの

### ・L298n
### ・ESP32(Devkit-C)
### ・モーター

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
## License
MIT License (Attribution Required — © 2025 TatsuyaM2667)
## 👨‍💻 作者
- [TatsuyaM2667](https://github.com/TatsuyaM2667)

