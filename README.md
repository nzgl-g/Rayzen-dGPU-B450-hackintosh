# B450-5600G-RX580-Hackintosh
OpenCore EFI for B450 Chipset Motherboard with AMD Ryzen 5 5600G Processor + Radeon RX 580 Graphics Card.

## Specification

- Motherboard     : Asus B450 M-K II
- CPU       : AMD Ryzen 5 5600G with Radeon Graphics
- RAM       : 2 x 16GB DDR4 3200Mhz
- Storage   : 500GB NvME
- dGPU      : AMD Radeon RX 580 8GB VRAM
- Ethernet  : Realtek RTL8111 Gigabit Ethernet
- Audio     : Realtek ALC892
- Boot Mode : UEFI
- OS : macOS BigSur

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
