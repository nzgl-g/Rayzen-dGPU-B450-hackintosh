# Rayzen-dGPU-B450-hackintosh
OpenCore EFI for B450 Chipset Motherboard with AMD Ryzen 6 cores with + Radeon RX 580 Graphics Card.

WARNING ⚠️: I  do not responsible for lost personal data, or malfunction hard drive. **You are doing this at your own RISK.**
|  Components             |         Requirements                |            Note                      |
|-------------------------|-------------------------------------|--------------------------------------|
| CPU                     |  6 cores AMD CPU                  |  This EFI is using a 6 cores kernel patch. If your CPU have more or less cores than this EFI, change it and refer to the OpenCore guide. |
| GPU                     |  AMD Radeon RX 580 8GB VRAM       |  |
| Motherboard             | B450 motherboards            |  This build will only work for the B450 motherboards, for other, please refer to the OpenCore Guide.|
| RAM                     | 2 x 8GB DDR4 3200Mhz  |  |
| Ethernet  | Realtek RTL8111 Gigabit Ethernet |  |
| Audio     | Realtek ALC892 | |
| OS | macOS BigSur | |

## Settings to change

|BIOS Settings|Toggle|
|-------------------------|-------------------------------------|
|Secure Boot|**OFF**|
|TPM|**OFF** (optional)|
|Above 4G Decoding|**ON**|
|VRAM for iGPU|Above 512M for best results|
|Fast Boot|**OFF**|
|CSM|**OFF**|
|Serial Port|**OFF**|

## Whats Work?

- CPU Power Management
- Shutdown and Restart
- Ethernet
- Bluetooth
- HDMI
- Audio (Rear & Front)
- TRIM Support for SSD
- Etc

## Tutorial
- From Zero Tutorial : https://dortania.github.io/OpenCore-Install-Guide/
- Creating the USB Installer : https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
- Generating SMBIOS : https://github.com/corpnewt/GenSMBIOS
- USB Fixes : https://dortania.github.io/OpenCore-Post-Install/usb/ and https://github.com/usbtoolbox/tool

Tutorial on "USB Fixes" related to the UTBMap.kext and SSDT-SLEEP.aml files. Please pay close attention to the guidelines that have been provided.
## Remark
- i have Asus B450-MKII , so please note that some usb ports won't work for u, if they didn't delete the USBMap.kext and use a compatible one for ure MB by using USBToolBox.
- if the OS not installed perfectly(missing gpu acceleration) please replace whatevergreen whith nootedred kexts
