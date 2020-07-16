# ESP8266 based  Homekit Air Purifier using [Xiaomi Air Filter](https://s.click.aliexpress.com/e/_dYLu1bZ)🌈
ESP8266 Based  HomeKit Air Purifier project using PMSx003 PM2.5 sensor, SHT3x temperature/humidity sensor, PWM controlled 12V fan and a Xiaomi Air Purifier Filter💨


------
[![Instagram URL](https://img.shields.io/twitter/url/https/www.instagram.com/homekidd?label=Follow&logo=instagram&style=social)](https://www.instagram.com/homekidd) [![FaceBook URL](https://img.shields.io/twitter/url/https/www.facebook.com/HomeKiid?label=Like&logo=facebook&style=social)](https://www.facebook.com/HomeKiid) [![YouTube URL](https://img.shields.io/twitter/url/https/www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA?label=Follow&logo=youtube&style=social)](https://www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA)
------

[![GitHub All Releases](https://img.shields.io/github/downloads/HomeKidd/HomeKit-Air-Purifier-ESP8266/total?color=green)](https://github.com/HomeKidd/Homekit-WS2812B-controller/releases) 
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/HomeKidd/HomeKit-Air-Purifier-ESP8266?color=yellow&label=Latest%20Release)](https://github.com/HomeKidd/HomeKit-Air-Purifier-ESP8266/releases) 
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CEYEK69ZYG69S&source=url)
<br/>
<br/>

## For usage and more information please read the [Wiki page](https://github.com/HomeKidd/HomeKit-Air-Purifier-ESP8266/wiki/)!

**Features:**

* PM2.5 and PM10 Air Quality sensor
* Temperature / Humidity sensor
* Manual / Automatic mode
* Fan speed control _(only in Manual mode)_
* Night/Silent mode
* Status light _(based on IAQ)_
* ~~Light sensor~~
* ~~OLED display~~
* Child Lock _(Enable/Disable button press via Eve app)_
* Power / Reset button
* ~~OTA firmware update~~ _(not implemented yet)_

**Demo:**

[![](http://img.youtube.com/vi/TG9xq7ccith0k/0.jpg)](http://www.youtube.com/ccwatch?v=TG9xq7ith0k "Demo Video")
<br/>
<img src="https://github.com/HomeKidd/Homekit-WS2812B-controller/raw/master/Imagecs/demo.jpg" class="center" width="500"/>

<br/>
<br/>

This project uses the Apple HomeKit accessory server library [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) from [@MaximKulkin](https://github.com/maximkulkin) for [ESP-OPEN-RTOS](https://github.com/SuperHouse/esp-open-rtos).<br/>

Although already forbidden by the sources and subsequent licensing, it is not allowed to use or distribute this software for a commercial purpose.<br/><br/>

<img src="https://freepngimg.com/thumb/apple_logo/25366-7-apple-logo-file.png" width="20"/> 

###### HomeKit Accessory Protocol (HAP) is Apple’s proprietary protocol that enables third-party accessories in the home (e.g., lights, thermostats and door locks) and Apple products to communicate with each other. HAP supports two transports, IP and Bluetooth LE. The information provided in the HomeKit Accessory Protocol Specification (Non-Commercial Version) describes how to implement HAP in an accessory that you create for non-commercial use and that will not be distributed or sold.

###### The HomeKit Accessory Protocol Specification (Non-Commercial Version) can be downloaded from the [HomeKit Apple Developer page.](https://developer.apple.com/homekit/)

###### Copyright © 2020 Apple Inc. All rights reserved.
