---
layout: article
title: "Start Raspberry Pi Headless Mode"
show_title: false
author: "KooMikoo"
categories: journal
sidebar:
  nav: docs-en
tags: [documentation,setup,raspberry pi]
image: https://cdn.mos.cms.futurecdn.net/RHC2LzMSx4zS3xHqkeatTH-970-80.png
---
# Start Raspberry Pi Headless Mode
1. Flash image to your Micro SD Card, eject and plug-in again to PC
2. Opened `boot` directory and make file `SSH` non-extention.
3. Eject and mount to raspberry pi then turn on devices.
4. Scan for IP Address Raspberry Pi using [AngryIpScanner](https://angryip.org/download/#windows) or [Wireless Network Watcher](https://www.nirsoft.net/utils/wireless_network_watcher.html).
5. Connect using SSH Client(such as [Putty](https://www.putty.org/)) or you can direct on Windows Terminal ```ssh pi@<ip_address_raspi>```
6. Congratulation, you can login using default credential `user/password` `pi/raspberry`.

UPDATE:
Alternatively, you can set it on latest version Raspberry Pi Imager then hitting Ctrl+Shift+X and enabling ssh through app before flash.

Source: [PiMyLifeup](https://pimylifeup.com/raspberry-pi-enable-ssh-boot/)
