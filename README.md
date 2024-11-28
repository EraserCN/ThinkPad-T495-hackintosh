# ThinkPad-E595-Hackintosh
 Hackintosh for ThinkPad T495.
 
![macOS running](img/os.png)


## Features
- **Working**: keyboard, trackpad, USB ports, Audio and GPU acceleration.
- **TBA**: Wi-Fi, Bluetooth, Sidecar, AirDrop, etc (Until I have a capable Wifi Card)
- **Won't Work at All**: Fingerprint, iPhone Mirroring(T2 Chip required), DRM-related stuff

## Prerequisites
- **My Hardware**:
   - Laptop Model: ThinkPad T495
   - CPU: AMD Ryzen 5 3500U 4c8t
   - Graphics: Integrated AMD Radeon Vega 8
   - Wifi Card: AX200(TBA)
   - SSD: SN580 512GB
- **macOS Version**: Tested with macOS Monterey.


## Installation Steps
1. Clone or download this repository.
2. Place the `EFI` folder into your bootable USB drive for macOS installation.
3. Boot from the USB drive and install macOS as per standard procedures.

## BIOS Settings
- Disable: TPM, Secure Boot, Memory Protection
- Enable: UEFI Only, AMD Virtualization, Hyper Thread

## Further Improvements
- ~~1. Audio support from AppleALC~~
2. Two-way AirDrop functionality
3. Better battery life
4. Readme in Chinese