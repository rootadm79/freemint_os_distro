# FreeMiNT OS Distro 26.1

> 🚀 Ready-to-boot FreeMiNT distribution for Atari Falcon, TT and accelerator systems

---

## ✨ Highlights

- 🧠 **Stable and refined** – major stability improvements in this release  
- ⚡ **Ready in minutes** – just flash and boot  
- 🖥️ **Modern Unix-like environment** on classic Atari hardware  
- 🌐 **Working networking out of the box** (NetUSBee / PicoWiFi)  
- 📦 **Package manager included** (RPM / sparemint)  
- 🧰 **Development-ready** – GCC, Python, Pure C and more  

---

## 🧾 Overview

FreeMiNT OS Distro is a complete, preconfigured operating system image designed for:

- **Atari Falcon (stock)**
- **Atari TT**
- Systems with **DFB1x** or **CT60/CT63 accelerators**

It delivers a fully functional Unix-like system with GUI, networking, development tools, and modern utilities — all ready to use immediately after boot.

---

## 💾 Installation

1. Download the image:  
   https://ns.mpsoftware.cz/filehosting/card.img  

2. Write it to SD / CF card:
   ```sh
   dd if=card.img of=/dev/sdX bs=1M status=progress
   ```

3. Insert the card into your Atari  
4. Boot from drive **C:**  

✔ Done — system boots directly into GUI

---

## 🧠 HDDRIVER

This distribution includes a **demo version of HDDRIVER**, kindly provided by Uwe Seimet.

⚠️ The demo version has limitations.

For full functionality, replace:
HDDRIVER.SYS

👉 Purchase full version:  
https://www.hddriver.net/

---

## ⚙️ Configuration

Main configuration file:
C:\MINT\1-19-cur\MINT.CNF

### 🖥️ Display

- Default: **640×480 / 256 colors**
- Videlity included, but disabled by default

---

### 🌐 Networking

Selectable in mint.cnf:

- NetUSBee
- PicoWiFi

---

## 📦 Included software

### 🧩 Core system

- Latest FreeMiNT kernel
- XaAES graphical environment
- TeraDesk desktop

---

### 🌍 Web browsers

- Links
- HighWire
- NetSurf

---

### 🧰 Development tools

- GCC
- Pure C
- Python
- GFA Basic

---

### 🔧 Utilities

- curl
- wget
- Midnight Commander (mc)

---

### 📦 Package management

- RPM packages via sparemint
- GUI package manager included

---

## 🆕 What’s new in 26.1

- Major stability improvements
- Cleaner configuration
- Better usability

---

## 🚀 Getting started

After boot:

- GUI starts automatically
- Use terminal or mc
- Try: links, netsurf

---

## 📌 Notes

- Actively maintained
- New release every ~6 months
- Easily extendable via RPM

---

## 📸 Screenshots

![Screenshot 1](screenshots/IMG_4926.jpeg)  
![Screenshot 2](screenshots/IMG_4927.jpeg)  
![Screenshot 3](screenshots/IMG_4929.jpeg)

---

## ❤️ Acknowledgements

- FreeMiNT community  
- sparemint project  
- Uwe Seimet  

---

## 📄 License

See individual components for licensing.
