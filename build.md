# Basic09 interpreter

### Build Linux
```
$ cd build
$ zaalang/zacc/bin/zacc -I zaalang/std -L zaalang/zrt/lib -O3 ../src/runb.zaa -lzrt
```

### Build Windows
```
> cd build
> zaalang\zacc\bin\zacc.exe -I zaalang\std -L zaalang\zrt\lib -O3 ..\src\runb.zaa -lzrt -lkernel32 -lbcrypt
```
