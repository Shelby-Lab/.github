# JuiceOSS | Juice Open Source Software

### Quick Source Initialization ###
```bash
- Release branch [PASS]
git clone https://github.com/OSS-juice-uwu/device_xiaomi_juice -b eleven-wip device/xiaomi/juice
git clone https://github.com/OSS-juice-uwu/vendor_xiaomi_juice -b eleven vendor/xiaomi/juice
git clone --depth=1 https://github.com/javashin/Xiaomi-Fury-Bengal-SD662 -b JuiceIcedSnow kernel/xiaomi/juice
git clone --depth=1 https://github.com/kdrag0n/proton-clang prebuilts/clang/host/linux-x86/clang-proton
```

### Build instruction ###
```bash
source build/envsetup.sh
lunch <rom>_juice-userdebug
Command for build
```
