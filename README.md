# Lenovo-X260-Opencore-EFI-Monterey

<td><img src="https://github.com/DobbyAkhmadi/Lenovo-X260-Opencore-EFI-Monterey/blob/main/Art/MySpesification.png" width="50%"></img> </td>

This is the fully detailed guide on how to create a working Hackintosh machine using:

* MacOS Monterey 12.1
* OpenCore 0.7.6
* Processor: Intel i5-6300U (6th-gen) Skylake
* RAM: 8 GB
* Graphics: Intel HD Graphics 520 2GB
* SSD: 256 GB SSD

This repository contains also `EFI` folder with all binaries produced meanwhile. The missing pieces might be however serial numbers or other hardware identifiers.

All parts of the PC work great. What is not working here is caused only by lack of proper hardware.

# Working

* MacOS Monterey 12.1
* Graphics Intel HD Graphics 520 2GB
* Ehernet I219V 
* Wireless AC8260
* HDMI audio
* TouchPad
* Bluetooth
* Front/Back Headphones Audio
* USB 2 2.0 & USB 3.0 gen. 1
* Any Camera Connected Via USB
* Any Headphoines Connected Via USB

# List Tools We Need

1. [OC Gen-X](https://github.com/Pavo-IM/OC-Gen-X) - Initial configuration creator
1. [ProperTree](https://github.com/corpnewt/ProperTree) - .plist editor, however Xcode works great too
1. [MountEFI](https://github.com/corpnewt/MountEFI) - To mount hidden boot partition (on both installer USB-stick & destination machine)
1. [SSDTTime](https://github.com/corpnewt/SSDTTime) - Generator of ACPI tables on destination hardware
1. [USBMap](https://github.com/corpnewt/USBMap) - Generator of dedicated USB port mapping kernel extension
1. [HackingTool by Headkaze](https://github.com/headkaze/Hackintool) - to verify settings on running macOS are fine; wasn't always working fine if `EFI` configuration had error on target machine


# Official Opencore

1. [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/) - Opencore Official Website
