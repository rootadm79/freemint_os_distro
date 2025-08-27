# FreeMiNT OS Distro
A complete bootable FreeMiNT distribution for 32-bit Atari machines.

## Overview
This project provides a ready-to-use FreeMiNT OS image for Atari Falcon, TT and compatible accelerators.  
It is designed to be easy to install, fully bootable and equipped with a modern Unix-like userland.

## Installation
- The release contains an image for a **4 GB card**  
- Write the raw image to your SD/CF card using `dd`, Balena Etcher or another imaging tool.  
- For advanced users: the repository also includes TAR archives for drives **C:** and **E.:**  
  - These are intended for **manual installation** only.  
  - The user must prepare the partitions, format them (C: as FAT12/16, E: as ext2) and copy the files manually.  
  - Recommended only for experienced users.
    
## Hardware requirements
- Works on base **Atari Falcon**, **DFB1x**, and **CT60/63 accelerators**.  
- Minimum: **14 MB RAM** (TT-RAM expansion highly recommended).  
- Display: preconfigured for **Videl 800×606, 256 colors**.  
  - If you experience problems, run **Videlity** and adjust settings for your monitor.  
- Networking supported: **NetUSBee** and **PicoWiFi**.

## Included software
- Up-to-date FreeMiNT **kernel**  
- **Unix backend** with many utilities  
- **XaAES** and **TeraDesk** desktop  
- **Links** web browser with latest SSL/TLS support  
- **Development tools**: Pure C, GCC, Python, GFA Basic and more  
- **New utilities**:  
  - `cURL` (latest version)  
  - `wget`  
  - `Midnight Commander (mc)`  
- **Online updater**

## Getting started
1. Write the image to your card and insert into your Atari.  
2. Boot the machine from drive **C:**.  
3. Log in to the desktop (TeraDesk + XaAES).  
4. Explore the preinstalled tools (`mc`, `links`, etc.) or start development with the included compilers.  

## Notes
- This distro is actively maintained.  
- For updates, use the included online updater.  
- Contributions and bug reports are welcome.
