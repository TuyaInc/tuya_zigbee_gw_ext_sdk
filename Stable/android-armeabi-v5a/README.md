
Cross Compiler Toolchain  
========================  

Andriod API > 23 (Android 6.0)

```  
arm-linux-androideabi-gcc (GCC) 4.9.x 20150123 (prerelease)
Copyright (C) 2014 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```

Compile  
=======  

Edit `Makefile`, append `-llog` to `LD_FLAGS` variable.

Production Testing  
==================   

You can download `Production Testing SDK` from https://github.com/TuyaInc/tuya_gw_pts_sdk.git. [Tuya Gateway Extension SDK Production Test description](https://docs.tuya.com/zh/iot/smart-product-solution/product-solutiongateway/gateway-extension-sdk-access-solution/tuya-gateway-extension-sdk-production-test-description?id=K9dudr9liqkgc) shows how to use it.
