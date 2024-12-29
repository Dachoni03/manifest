![428353472_778010837683362_3150116218403282690_n](https://github.com/user-attachments/assets/edf4d366-3958-454a-ba6e-3b1b191a8712)

PixelStar
===========

[**Download**](https://sourceforge.net/projects/pixelstar/files/)

## Things that will help you getting started ##
- [Pixelstar-devices](https://github.com/pixelstar-devices)
- [Flags](https://github.com/Project-PixelStar/Flags)

#### Note ####
- Make sure git-lfs is installed

  ### Sync ###

  ```bash
  git lfs install

repo init -u https://github.com/Project-PixelStar/manifest -b 15 --git-lfs

repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
### Build ###

```bash
. build/envsetup.sh
lunch pixelstar_$device-<|userdebug/user/eng|>
mka bacon -jXT
```

## Important Links ##
- [Telegram Announcement Channel](https://t.me/pixelstarchannel)
- [Telegram Discussion Group](https://t.me/Project_PixelStar)

# Credits:

 * [**Android Open Source Project**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**ParanoidAndroid**](https://github.com/AOSPA)
 * [**crDroid**](https://github.com/crdroidandroid)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**YAAP**](https://github.com/yaap)
 * [**PixysOS**](https://github.com/PixysOS)
 * [**Havoc-OS**](https://github.com/Havoc-OS)
 * [**ColtOS**](https://github.com/Colt-Enigma)
 * [**TheParasiteProject**](https://github.com/TheParasiteProject)
 * [**ThePixelProject**](https://github.com/The-Pixel-Project)

* And tons of other ROMs not mentioned above
