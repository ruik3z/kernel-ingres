# Avalon Kernel

Avalon is a NetHunter-focused custom kernel for the Poco F4 GT (ingres).

Built on the LineageOS 23.2 kernel source base with additional wireless adapter, SDR and penetration testing support for Kali NetHunter.

## Features

* KernelSU-Next integration
* Kali NetHunter support
* External USB WiFi adapter support
* SDR support
* Monitor mode capable chipset support
* Additional firmware loading support for NetHunter environments

## Device

* Xiaomi Poco F4 GT (ingres)

## Source Structure

This repository contains:

* Kernel source
* Device trees
* SM8450 common sources
* Vendor modules
* Build configuration used for Avalon releases

## Building

Use the included "ingres_user_defconfig" configuration.

Kernel compilation should be performed using the Android LLVM toolchain compatible with the LineageOS 23.2 source tree.

## Credits

### LineageOS 23.2 Base

Huge thanks to itzparsaYC for bringing LineageOS to ingres.

Special thanks to n08i40k for extensive testing and developments.

### Additional Credits

* ArianK16a for SM8450 sources
* KernelSU-Next developers
* Kali NetHunter developers
* LineageOS project
* All testers and contributors

## License

This project contains Linux kernel source code licensed under GPLv2.

See the LICENSE file for details.
