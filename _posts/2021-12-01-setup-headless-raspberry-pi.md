---
layout: article
title: "Start Journey On Raspberry Pi"
show_title: false
author: "KooMikoo"
categories: journal
sidebar:
  nav: docs-en
tags: [documentation,setup,raspberry pi]
article_header:
  type: cover
  image:
    src: https://cdn.mos.cms.futurecdn.net/RHC2LzMSx4zS3xHqkeatTH-970-80.png
---
# Memulai Raspberry Pi

## Cerita Dibalik Raspberry Pi
Raspberry Pi (/paɪ/) adalah seri single-board computers (SBCs) terkecil yang dikembangkan di United Kingdom (Inggris) oleh Raspberry Pi Foundation yang berkerjasama dengan Broadcom. Projek Raspberry Pi sebenarnya digunakan untuk keperluan pembelajaran di sekolah dan negara-negara berkembang.

<img class="image image--md" src="https://projects-static.raspberrypi.org/projects/raspberry-pi-setting-up/0d6033edf45ad2d4185ed05d6cd9a01e2f803034/en/images/pi-plug-in.gif"/>

Sampai dengan saat ini Raspberry Pi Foundation atau yang sekarang disebut Raspberry Pi Trading sudah mengeluarkan berbagai jenis tipe Raspbery Pi yang mendukung untuk berbagai macam projek.

| Jenis          | Tipe      | SOC     | Memory  | Release | Arsitektur |
|----------------|-----------|---------|---------|---------|------------|
| Raspberry Pi   | B         | BCM2835 | 256MB | 2012 | ARMv6Z (32-bit) |
|       -        | A         | BCM2835 | 256MB | 2013 | ARMv6Z (32-bit) |
|       -        | B+        | BCM2835 | 512MB | 2014 | ARMv6Z (32-bit) |
|       -        | A+        | BCM2835 | 512MB | 2014 | ARMv6Z (32-bit) |
| Raspberry Pi 2 | B         | BCM2836/7 | 1 GB | 2015 | ARMv7-A (32-bit) |
| Raspberry Pi Zero | Zero   | BCM2835   | 512MB | 2015 | ARMv6Z (32-bit) |
|         -         | W/WH   | BCM2835   | 512MB | 2017 | ARMv6Z (32-bit) |
|         -         | 2W     | BCM2710A1 | 512MB | 2021 | ARMv8-A (64/32-bit) |
| Raspberry Pi 3 | B  | BCM2837A0/B0 | 1GB | 2016 | ARMv8-A (64/32-bit) |
|        -       | A+ | BCM2837B0 | 512MB  | 2018 | ARMv8 (64-bit) |
|        -       | B+ | BCM2837B0 | 1GB    | 2018 | ARMv8-A (64/32-bit) |
| Raspberry Pi 4 | B   | BCM2711 | 1GB,2GB,4GB,8GB | 2019 | ARMv8-A (64/32-bit) |
|       -        | 400 | BCM2711 | 4GB             | 2020 | ARMv8-A (64/32-bit) |
| Raspberry Pi Pico | N/A | RP2040 | 264 KB | 2021 | Armv6-M |

## Apa yang dibutuhkan
1. Raspberry Pi
<br>Dari berbagai jenis Raspberry Pi diatas, pilih sesuai kebutuhan dan projek mu. Bila membuat sesuatu yang compact bisa memilih jenis Zero.</br>
2. Power Supply Adaptor
<br>Adaptor yang dibutuhkan berdaya 5V dengan tegangan min 2.5 Amps ~ 3.0 Amps.</br>
3. Micro SD Card.
<br>Berkapasitas minimal 8GB.</br>
4. Keyboard dan Mouse
5. Layar TV atau Komputer
6. Kabel HDMI
<br>Bila VGA/DVI gunakan konverter-ke-HDMI.</br>
8. Casing
9. Headphone / Speaker
10. Kabel Ethernet

## Persiapan SD Card

## Enable SSH on First Boot
1. Flash image to your Micro SD Card, eject and plug-in again to PC
2. Opened `boot` directory and make file `SSH` non-extention.
3. Eject and mount to raspberry pi then turn on devices.
4. Scan for IP Address Raspberry Pi using [AngryIpScanner](https://angryip.org/download/#windows) or [Wireless Network Watcher](https://www.nirsoft.net/utils/wireless_network_watcher.html).
5. Connect using SSH Client(such as [Putty](https://www.putty.org/)) or you can direct on Windows Terminal ```ssh pi@<ip_address_raspi>```
6. Congratulation, you can login using default credential `user/password` `pi/raspberry`.

UPDATE:
Alternatively, you can set it on latest version Raspberry Pi Imager then hitting Ctrl+Shift+X and enabling ssh through app before flash.

Source: [PiMyLifeup](https://pimylifeup.com/raspberry-pi-enable-ssh-boot/)
