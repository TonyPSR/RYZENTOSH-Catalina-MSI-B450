# RYZENTOSH-Catalina-MSI-B450

## Specs

| Component           | Detail                                              |
| ------------------- | --------------------------------------------------- |
| Processor           | AMD Ryzen 7 2700 8C/16T (non-X)                         |
| Motherboard         | MSI B450 TOMAHAWK MAX                               |
| Memory              | 16GB(8x2) Crucial Ballistix DDR4 3000 MHz           |
| SSD                 | Crucial BX500 120GB                                 |
| iGPU                | None                                                |
| Graphics Card       | GIGABYTE NVIDIA GeForce GT 710 2GB DDR3             |
| Monitor             | HP 24es 1080p IPS (24inch)                          |
| Sound Card          | Realtek ALC892 Codec                                |
| LAN                 | Realtek® 8111H Gigabit LAN controller               |

> OpenCore Version: 0.6.7

> MacOS supported: macOS 10.15.x Catalina

# Don't forget to update MLB, SystemSerialNumber and SystemUUID under PlatformInfo key in config.plist!!!
#### For macOS Catalina, use iMac14,2 SMBIOS.

## What's working?
- Full Hardware Acceleration
- Audio (Speaker + Headphone)
- Ethernet
- External Devices
  - Webcam
  - Mic

## What's Not Working?
- Applications using Intel Virtualization Technology
  - Android Emulators (use physical devices or Genymotion Android Emulator)
  - Docker Engine (there are workarounds but not recommended)
- Sleep (Fix: Disable sleep in System Preferences)

## Not Tested
- iServices (Facetime, iMessage...)
- Adobe Suite
- Wi-Fi & Bluetooth dongles
- USB 3.1

## Important Links
1. OpenCorePkg: https://github.com/acidanthera/OpenCorePkg
2. GenSMBIOS: https://github.com/corpnewt/GenSMBIOS
3. ProperTree: https://github.com/corpnewt/ProperTree
4. MountEFI: https://github.com/corpnewt/MountEFI
5. SSDTTime: https://github.com/corpnewt/SSDTTime
6. AMD Power Gadget(optional): https://github.com/trulyspinach/SMCAMDProcessor/releases

## macOS 11 Big Sur build: https://github.com/TonyPSR/RYZENTOSH-BigSur-MSI-B450

