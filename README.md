Overview  
========  

TUYA_GW_EXT_SDK is a development kit which consists of library and APIs. We can use it to develop gateway product.  

Features  
========  

- Register to Tuya Cloud Platform  
- Support all ZigBee device in Tuya Ecosystem  
- Access other wireless device is available, such as 433, ZWave, KNX and so on  
- Access ZigBee device which isn't in Tuya Ecosystem  
- Realtime manage smart device by Tuya Smart APP
- Turn traditional router into ZigBee gateway without any development  

How to Use  
==========  

[Tuya Gateway Extension SDK Demo Description](https://docs.tuya.com/zh/iot/device-development/access-mode-product-solution/product-solutiongateway/gateway-extension-sdk-access-solution/tuya-gateway-extension-sdk-demo-description)  

SDK Development Manual   
======================  

[Tuya Gateway Extension SDK Development Manual](https://docs.tuya.com/zh/iot/device-development/access-mode-product-solution/product-solutiongateway/gateway-extension-sdk-access-solution/tuya-gateway-extension-sdk-development-manual)  


SDK Package  
===========  

| Package Name                                                 | Description          |
| ------------------------------------------------------------ | -------------------- |
| tuya_zigbee_gw_ext_sdk_\<version\>\_wired\_\<toolchain\>.tar.gz  | Wired Gateway        |
| tuya_zigbee_gw_ext_sdk_\<version\>\_wifi\_\<toolchain\>.tar.gz   | WiFi Gateway         |
| tuya_zigbee_gw_ext_sdk_\<version\>\_wifi_wired\_\<toolchain\>.tar.gz | WiFi + Wired Gateway |

Supported Platforms  
===================  

Ubuntu x64  
----------  

* linux-ubuntu-6.2.0_64Bit  

Hisilicon  
---------  

* arm-himix200-linux

REALTEK  
-------  

* mips-linux-uclibc-gcc-4.4.7 for RTL8197 
* rsdk-4.6.4 for RTL8196

MStar  
-----  

* gcc-linaro-6.3.1-2017.05-x86_64_arm-linux-gnueabihf  

新唐N32926  
----------  

* arm-nuvoton-linux-uclibceabi  

MediaTek  
--------  

* mipsel-openwrt-linux-uclibc-0.9.33.2-gcc-4.8.3
