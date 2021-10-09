##### [Home repo](https://github.com/overwasher/home/) | [Overwatcher code](https://github.com/overwasher/overwatcher) | [Sensor Node code](https://github.com/overwasher/esp-firmware) | [Telegram bot code](https://github.com/overwasher/telegram-bot) | [Task Tracker](https://taiga.dcnick3.me/project/overwasher/)

# Overwasher: sensor-node-hardware

This repository contains hardware design files and some renders of them. More specifically - schematic and PCB layout.

![pcb 3d view](https://raw.githubusercontent.com/overwasher/sensor-node-hardware/master/3DVIEW_RENDER.png)

### Components

- ESP32 chip (with Wi-Fi module)
- LIS2DH12 accelerometer
- An LDO regulator to power the chip from 3.7-5v (either from the wall or LiPo battery)

The .json files can be opened with [EasyEDA designer](https://easyeda.com/editor) and edited.
