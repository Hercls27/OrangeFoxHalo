## Custom Recovery | Device Tree
[Lenovo leLegion Y70]
| Device                  | Lenovo Legion Y70                                          |
| ----------------------- | ---------------------------------------------------------|
| SoC                     | Qualcomm SM8475 Snapdragon 8+ Gen 1 (4 nm)                      |      
| CPU                     | 1x 3.2 GHz Cortex•X2 +3x 2.8 GHz Cortex•A710 + 4x 2.0 GHz Cortex•A510  |
| GPU                     | Adreno 730                                             |
| Internal                | 256GB 12GB RAM, 512GB 16GB RAM, UFS 3.1                 |
| Model                   | Y70 |
| Codename                | Halo |

## Device picture

![Lenovo Legion Y70](https://fdn2.gsmarena.com/vv/pics/lenovo/lenovo-legion-y70-1.jpg)

### Release Notes
* Orangefox/TWRP now boots, decryption is working fine but aren't tested in GSI.
* Lenovo Legion Y70 is Virtual A/B with dedicated Recovery Partition, no need to `boot` it like other A/Bs, just `flash` it.

### Working Features
* Internal Storage
* FastbootD
* ADB Commands and Terminal
* Flashing .zip files.
* Flashing Firmware
* Flashing non-logical .img files.
* ADB Sideload
* MTP

### Issues and Bugs
* Flashing OTA. (need test)
* Vibration/Haptics

### Credits
```
# Copyright (C) 2023 The Android Open Source Project
# Copyright (C) 2023 SebaUbuntu's TWRP device tree generator
# SPDX-License-Identifier: Apache-2.0
```
