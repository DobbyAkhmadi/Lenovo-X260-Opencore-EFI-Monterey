# Lenovo-X260-Opencore-EFI-Monterey

This is the fully detailed guide on how to create a working Hackintosh machine using:

* macOS Monterey 12.1
* OpenCore 0.7.6
* processor: Intel i5-6300U (6th-gen) Skylake
* RAM: 8 GB
* GFX: Intel HD Graphics 520 2GB
* SSD: 256 GB SSD

This repository contains also `EFI` folder with all binaries produced meanwhile. The missing pieces might be however serial numbers or other hardware identifiers.

All parts of the PC work great. What is not working here is caused only by lack of proper hardware.

Working:

* macOS Monterey 12.1
* graphics HD display
* Ehernet I219V 
* Wireless AC8260
* HDMI audio
* TouchPad
* Bluetooth
* front/back headphones audio
* USB 2 2.0 & USB 3.0 gen. 1
* any camera connected via USB
* any headphoines connected via USB

List of needed tools:

1. [OC Gen-X](https://github.com/Pavo-IM/OC-Gen-X) - initial configuration creator
1. [ProperTree](https://github.com/corpnewt/ProperTree) - .plist editor, however Xcode works great too
1. [MountEFI](https://github.com/corpnewt/MountEFI) - to mount hidden boot partition (on both installer USB-stick & destination machine)
1. [SSDTTime](https://github.com/corpnewt/SSDTTime) - generator of ACPI tables on destination hardware
1. [USBMap](https://github.com/corpnewt/USBMap) - generator of dedicated USB port mapping kernel extension
1. [HackingTool by Headkaze](https://github.com/headkaze/Hackintool) - to verify settings on running macOS are fine; wasn't always working fine if `EFI` configuration had error on target machine
