# tuya_zigbee_gw_ext_sdk

## overview

tuya_zigbee_gw_ext_sdk is an integrated library&APIs, primarily for developing gateway products: Zigbee gateway, ZWAVE gateway and so on.


feature :

* support many zigbee sub-devices, meanwhile developer extend to support their zigbee device or other type gateway product such as ZWAVE, 433 gateway.
* Register to Tuya Cloud platform.
* Realtime control sub-devices via Tuya Smart APP

| SDK package     |  explain        |
|---------------|-----------------------|
|tuya_zigbee_gw_ext_sdk_<version>_pegasus_<toolchain name>.tar.gz | pegasus + wired  |
|tuya_zigbee_gw_ext_sdk_<version>_wifi_<toolchain name>.tar.gz  | wifi gateway |
|tuya_zigbee_gw_ext_sdk_<version>_wifi_wired_<toolchain name>.tar.gz | wired + WIFI gateway |

## how to use

### run a quick demo

1) edit Makefile, and set COMPILE_PREX ?= to absolute path of your toolchain gcc.

2) compile one application.

```bash
make
```
## SDK manual 

[TUYA DOCS center](https://docs.tuya.com/zh/iot/device-development/access-mode-product-solution/product-solutiongateway/linux-sdk-solution-gateway/tuya-zigbee-gateway-extend-sdk-users-manual)

## supported platforms

### ubuntu x64

* linux-ubuntu-6.2.0_64Bi

### Qualcomm


* arm_cortex-a7_gcc-5.2.0_uClibc-1.0.14_eabi for IPQ4019

* mips-openwrt-linux-gnu-gcc-5.4.0 for QCA9531

### Hisilicon

* arm-himix200-linux

### REALTEK rtl819x

* mips-linux-uclibc-gcc-4.4.7

### nuvoton

* arm-nuvoton-linux-uclibceabi for N32926

### MTK

* mipsel_24kc_gcc-6.3.0_musl-1.1.16 for MT7621 

* mipsel-openwrt-linux-uclibc-0.9.33.2-gcc-4.8.3 for MT7621


### ECONET

* mipsel-linux-uclibc-4.6.3-kernel3.18 for EN7561DU


