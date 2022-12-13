# Initial setup

## 1. Extract supporting libraries and head files

```
~/hdz_goggle/code$ tar xzvf linux-4.9.tar.gz
~/hdz_goggle/code$ cat media.tar.gzaa media.tar.gzab > media.tar.gz
~/hdz_goggle/code$ tar xzvf media.tar.gz
~/hdz_goggle/code$ tar xzvf toolchain.tar.gz
```

## 2. Setup cmake environment

```
~/hdz_goggle/workspace/code$./setup.sh
```

# Build code

```
 ~/hdz_goggle/code/$cd build
 ~/hdz_goggle/code/build$make clean all
```

the firmware is generated on ~/hdz_goggle/code/out/HDZERO_GOGGLE-x.x.x.bin
Where x.x.x is the OTA_VER.RX_VER.VA_VER
