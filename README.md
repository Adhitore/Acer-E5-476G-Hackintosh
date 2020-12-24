# Acer E5-476G

THIS IS FORK FROM ROCKAVOLDY REP. THIS EDIT FOR MY OWN BACKUP. PLEASE REFERS TO THE PARENT REP FOR ANY CHANGES. 
Donate to author:
[![ko-fi](https://img.shields.io/badge/Ko--fi-rockavoldy-brightgreen?style=flat&logo=ko-fi)](https://ko-fi.com/rockavoldy)
[![trakteer.id](https://img.shields.io/badge/Trakteer.id-akhmad.id-brightgreen?style=flat&logo=ko-fi)](https://trakteer.id/akhmad.id)

## Specifications

- Processor: Intel Core i3-6006U @2.0GHz
- Memory: 8GB DDR4 Dual Channel @2133MHz
- Integrated GPU: Intel HD Graphics 520
- Discrete GPU: Nvidia MX130
- Audio: Realtek ALC255
- Storage: HDD Seagate 5200rpm (default one)
- Ethernet Card: Realtek RTL8111
- Wireless Card: Intel 3168NGW
- Touchpad: ELAN0501 I2C
- Keyboard: PS2 Keyboard
- Resolution: 1366x768@60Hz
- Bootloader: OpenCore 0.6.4 RELEASE
- OS Version: macOS 11.1 Big Sur (20C69)
- SMBIOS: MacBookPro13,1

## Working

- Power Management, idle @500-800MHz
- Shutdown, Restart, Sleep
- QE/CI Intel HD Graphics 520
- Intel Wireless
- Brightness
- Battery up to 6 hours
- Ethernet RTL8111
- Trackpad Full gestures
- Keyboard
- USB 3.0
- VGA Port
- HDMI Port + HDMI Audio out
- Speaker + Combo Jack Headphone

## Not Working

- Nvidia MX130 (Optimus)
- Combo Jack Microphone
- SD Card reader (USB Interface, not supported yet)
- Sealed Broken

## Notes
- Remap Brightness keys to PrtScr & Pause Break. And Volume keys to Fn+F11 (NumLock) & Fn+F12 (ScrLock). And i am also disable Fn+Arrow key, you can see SSDT-PS2K to change this if you don’t like my mapping.
- Use your own generated SMBIOS as this rep doesn't included one.
-  ~~Jack Audio broken if you are not installing ALC255 [ComboJackFix from hackintosh-stuff!](https://github.com/hackintosh-stuff/ComboJack)~~ Use [ComboJack from lvs1947](https://github.com/lvs1974/ComboJack)
- If your CPU idling at 1.3ghz or above, please genereate your own CPUFriend and CPUDataProvider.


## Credit

- Rockavoldy for his time and work on original rep and time to chat with me solving hackintosh along the way
- Acidanthera team
- Alexandred and VoodooI2C team
- OpenIntelWireless team
- RehabMan
- Andres
- And many other people in hackintosh community
