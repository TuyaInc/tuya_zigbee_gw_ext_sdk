
Cross Compiler Toolchain  
========================  

```  
arm-linux-gnueabihf-gcc (crosstool-NG linaro-1.13.1-4.7-2013.02-01-20130221 - Linaro GCC 2013.02) 4.7.3 20130205 (prerelease)
Copyright (C) 2012 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

```

Compile  
======= 

Edit `Makefile`, append `-lrt` to `LD_FLAGS` variable.

Production Testing  
==================   

You can download `Production Testing SDK` from https://github.com/TuyaInc/tuya_gw_pts_sdk.git. [Tuya Gateway Extension SDK Production Test description](https://docs.tuya.com/zh/iot/smart-product-solution/product-solutiongateway/gateway-extension-sdk-access-solution/tuya-gateway-extension-sdk-production-test-description?id=K9dudr9liqkgc) shows how to use it.
