---
title: InfiniTime CMake Options
date: 2021-11-25 17:46:43
tags: 
- Programming
cover: https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fapi.cocoachina.com%2Fuploads%2Fimage%2F20200302%2F1583116203870375.jpg&refer=http%3A%2F%2Fapi.cocoachina.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1640425793&t=621d7a5ff58c96583b4a142b7c0aa219
---
### Settings -> Build, Execution, Deployment -> CMake
``` bash 
-DCMAKE_BUILD_TYPE=Debug
-DCMAKE_SYSTEM_NAME=Generic
-DARM_NONE_EABI_TOOLCHAIN_PATH=D:/CpnyFile/Richard/PineTime/Dependencies/gcc-arm-none-eabi-10-2020-q4-major
-DNRF5_SDK_PATH=D:/CpnyFile/Richard/PineTime/Dependencies/nRF5_SDK_17.0.2_d674dde
-DUSE_JLINK=1
-DNRFJPROG=D:/CpnyFile/Richard/PineTime/Dependencies
-DBUILD_DFU=1
```