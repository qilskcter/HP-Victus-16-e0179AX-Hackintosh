 # <div align="center">HP Gaming Victus 16-e0179AX Hackintosh</div> 

This EFI is undone because this Laptop's NVMe is unsupported, so I can't install macOS in this Laptop. If you want to contribute to this repository, you can fork this repo and update this EFI. Thank you!

## Intro

| | Version |
|-|---------|
| OpenCore | 0.9.3 Mod |
| macOS | Big Sur - Ventura |

## Laptop Specification

|                     | Specifications| Note |
| ---------------------------- | ---------------------- |------------------|
| ``CPU``| AMD Ryzen™ 5 5600H 3.30GHz |  |
| ``Memory``| 8GB DDR4-3200MHz |  |
| ``iGPU``| AMD Radeon™ Graphics | Using [NootedRed](https://github.com/NootInc/NootedRed) |
| ``dGPU``| NVIDIA GeForce RTX 3050 Ti 4 GB | NOT SUPPORTED |
| ``Disk``| SK hynix PC711 HFS512GDE9X073N | NOT SUPPORTED |
| ``Screen``| 16.1" 1920 x 1080 |    |
| ``Ethernet``| RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | Use [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases). |
| ``WiFi and Bluetooth``| RTL8852AE 802.11ax PCIe Wireless Network Adapter | Realtek Wifi card is NOT SUPPORTED in any macOS. | 
| ``Audio``| ALC245 | Add `alcid=11` to boot-arg or add layout-id to DeviceProperties. |
| ``Keyboard``| - |  |
| ``Touchpad``| Synapstic Precision Touchpad |  |
| ``Battery``| 4-cell lithium polymer | |
| ``Dimensions``| 23.5mm x 369mm x 260mm |     |
| ``Weight``| 2.46kg |     |

## Features (NOT TESTED ❌)

