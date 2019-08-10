# Hackintosh HP ProBook 650 G1

This repo contains my configuration, kexts, etc of my working hackintosh.

## macOS versions

List of supported versions:

- macOS Mojave
    - 10.14.6 [(checkout this branch)](https://github.com/Hologos/hackintosh-hp-probook-650-g1/tree/10.14.6)
    - 10.14.5 [(checkout this branch)](https://github.com/Hologos/hackintosh-hp-probook-650-g1/tree/10.14.5)
    - 10.14.4 [(checkout this branch)](https://github.com/Hologos/hackintosh-hp-probook-650-g1/tree/10.14.4)

## Specs

**BIOS:** L77 (ver. 01.46)

**CPU:** Intel Core i5 4200M @ 2.5 GHz (Haswell, 2 core, 4 HT)

**Chipset:** Intel 8 Series

**GPU:** integrated Intel HD Graphics 4600

**Display:** 1920x1080

**Ethernet:** Intel I217V

**Wifi + BT:** BCM94352HMB/AW-CE123H (Mini PCI-E, supports WiFi/ac and BT4LE)

## Installation

***Notice: you have to generate your own SMBIOS/SerialNumber, SMBIOS/BoardSerialNumber and SMBIOS/SmUUID.***

You can either install your hackintosh all by yourself or you can use my EFI folders to install and run the hackintosh.

To install hackintosh on your laptop, follow these 2 guides:

- [[Guide] Booting the OS X installer on LAPTOPS with Clover](https://www.tonymacx86.com/threads/guide-booting-the-os-x-installer-on-laptops-with-clover.148093/)
- [[Guide] HP ProBook/EliteBook/Zbook using Clover UEFI hotpatch](https://www.tonymacx86.com/threads/guide-hp-probook-elitebook-zbook-using-clover-uefi-hotpatch.261719/)

## Issues

*More info can be found inside corresponding issue.*

- Clover boot screen has terrible screen resolution ([#1](https://github.com/Hologos/hackintosh-hp-probook-650-g1/issues/1))
