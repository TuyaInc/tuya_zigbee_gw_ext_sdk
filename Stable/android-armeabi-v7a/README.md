
## Cross Compiler Toolchain  

Andriod API > 16 (Android 4.1)

```  
Android (4751641 based on r328903) clang version 7.0.2 (https://android.googlesource.com/toolchain/clang 003100370607242ddd5815e4a043907ea9004281) (https://android.googlesource.com/toolchain/llvm 1d739ffb0366421d383e04ff80ec2ee591315116) (based on LLVM 7.0.2svn)
Target: armv7a-none-linux-android16
Thread model: posix
```

## Compile  

Edit `Makefile`, append `-llog` to `LD_FLAGS` variable.
