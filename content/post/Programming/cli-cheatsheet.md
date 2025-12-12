---
title: CLI Cheatsheet
date: 2023-08-08 17:51:59
tags:
- Programming
cover: https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fapi.cocoachina.com%2Fuploads%2Fimage%2F20200302%2F1583116203870375.jpg&refer=http%3A%2F%2Fapi.cocoachina.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1640425793&t=621d7a5ff58c96583b4a142b7c0aa219
---
### Apache
``` bash
httpd -k start -n Apache24

httpd -k stop -n Apache24
```

### Powershell
``` bash
powercfg /batteryreport

Get-FileHash -Algorithm SHA256 ./filename
```

### Expo
``` bash
npx expo run:android

eas build --platform android --profile preview 
```

### Windows installation
When you reach the "Let's connect you to a network" screen during the Windows 11 installation, do not connect to any network.

Press Shift + F10 on your keyboard to open a Command Prompt window. (On some laptops, you might need to press Fn + Shift + F10.)

In the Command Prompt, type the following command exactly as it appears and press Enter:

Method 1: Using the OOBE\BYPASSNRO Command (Most Common)
``` bash
OOBE\BYPASSNRO
```

Method 2: Using start ms-cxh:localonly (For Newer Builds or if BYPASSNRO Fails)
``` bash
start ms-cxh:localonly
```