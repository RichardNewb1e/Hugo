---
title: nRF Sniffer for BLE with Wireshark
date: 2022-03-06 12:15:10
tags:
- Programming
cover: https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fapi.cocoachina.com%2Fuploads%2Fimage%2F20200302%2F1583116203870375.jpg&refer=http%3A%2F%2Fapi.cocoachina.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1640425793&t=621d7a5ff58c96583b4a142b7c0aa219
---
# Hardware
- nRF52832
- CH340 Max speed 3Mbps
- CP2102 Max speed 1Mbps ==May work with sniffer 51296 firmware only==

# Software
## Wireshark
```
Global Extcap path		D:\Program Files\Wireshark\extcap		Extcap Plugins path

Personal configuration		C:\Users\fsky\AppData\Roaming\Wireshark\profiles		BLE profile path
```
## nrf_sniffer.bat with Python2 only

First modify .bat file
``` bash 
@echo off
"D:\Python\Python27\python" "%~dp0nrf_sniffer.py"  %*
```
then run it in cmd with:
```
nrf_sniffer.bat --extcap-interfaces
```
## nrf_sniffer_ble.bat with Python3 only

run it in cmd with:
```
nrf_sniffer_ble.bat --extcap-interfaces
```
