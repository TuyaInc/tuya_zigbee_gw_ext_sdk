
Cross Compiler Toolchain  
========================  

Andriod API > 16 (Android 4.1)

```  
Android (4751641 based on r328903) clang version 7.0.2
(https://android.googlesource.com/toolchain/clang
    003100370607242ddd5815e4a043907ea9004281)
(https://android.googlesource.com/toolchain/llvm
    1d739ffb0366421d383e04ff80ec2ee591315116) (based on LLVM 7.0.2svn)
Target: armv7a-none-linux-android16
Thread model: posix
```

Compile  
=======  

Edit `Makefile`, append `-llog` to `LD_FLAGS` variable.

Production Testing  
==================   

You can download `Production Testing SDK` from https://github.com/TuyaInc/tuya_gw_pts_sdk.git. [Tuya Gateway Extension SDK Production Test description](https://docs.tuya.com/zh/iot/smart-product-solution/product-solutiongateway/gateway-extension-sdk-access-solution/tuya-gateway-extension-sdk-production-test-description?id=K9dudr9liqkgc) shows how to use it.

