- [My Home Assistant config](#my-home-assistant-config)
  - [Host](#host)
    - [HP T630](#hp-t630)
    - [Proxmox](#proxmox)
  - [Hardware](#hardware)
    - [SystemAir](#systemair)


# My Home Assistant config

The repository contains my configuration for my HA. Feel free to comment or reach out me via TG, email etc.

## Host

### HP T630

I moved from RPi3 to HP. Now it's much faster and stable.
CPU: AMD GX-420GI Radeon R7E
Memory: 8GB RAM
Storage: 128GB SSD M.2
Storage 2: NATEC Kangaroo Dual with 2 x 2TB HDD Toshiba (Duplicate software RAID)

### Proxmox

I am running HA as OS in Virtual Machine hosted on Proxmox. Other containers:
- Unifi
- PiHole
- Papaerless
- PhotoPrism
- OpenMediaVault

## Hardware

Currently I use:
- Sonoff Zigbee 3.0 USB Dongle as Zigbee Hub
- Xiaomi Vaacum Mop Pro
- ESP8266
- ESP32
- Philips Hue Bridge with 3x LED Bulbs
- Philips 4Button Remote Control Zigbee
- LG Air Conditioner
- Tuya Smart Socket Wifi
- Tuya Smart Socket Zigbee
- Tuya Smart Switch 4x Zigbee
- Xiaomi Aqara Weather
- Zamel MEW-01 Electricity meter via MQTT
- HIKVision Cameras
- Waveshare WSDEV0001 (RS485 Modbus host)
- SystemAir SAVE VTR300 via Modbus

### SystemAir

Niestety dokumentacja udostępniona przez producenta jest błędna i w kiepskim formacie dlatego dla potomnych zamieszczam tutaj poprawione już pliki zawierające encje dla HomeAssistanta.
Oficjalna dokumentacja z której korzystałem to:
https://shop.systemair.com/upload/assets/SAVE_MODBUS_VARIABLE_LIST_20190116__REV__29_.PDF

W adresach jest błąd, od każdej wartości należy odjąć 1.

