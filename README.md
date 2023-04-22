# ThinkPad E14 Hackintosh

 <p align="center">
    <a href="https://www.apple.com/macos/ventura/">
        <img src="https://img.shields.io/badge/macOS-Ventura_13.2-orange.svg"/>
    </a>
    <a href="https://github.com/acidanthera/OpenCorePkg">
        <img src="https://img.shields.io/badge/OpenCore-0.8.8-blue.svg"/>
    </a>
</p>

OpenCore-based EFI for Lenovo ThinkPad E14 | Model 20RA

I'm back to Linux, and bye bye macOS, I uploaded this repository before rm -rf /, for reference only, this repository should not be updated in the future.

# Contect

- Intro
- Disclaimer
- Devices
- Work/Issues/Not Work
- Before / After Installation
- Other Respositories
- Credits

# Intro

This includes an EFI(Opencore) which works on Hackintosh the ThinkPad ThinkPad E14

# Disclaimer

Your warranty is now void. Please do some research if you have any concerns before utilizing my project. I am not responsible for any loss, including but not limited to Kernel Panic, device fail to boot or can not function normally, storage damage or data loss, atomic bombing, World War III, The CK-Class Restructuring Scenario that SCP Foundation can not prevent, and so on.

# Devices

| Category  | Component                                       | Note                                                         |
| --------- | ----------------------------------------------- | ------------------------------------------------------------ |
| Type | 20RA | - |
| CPU | Intel Core i3-10110U | - |
| GPU | Intel UHD Graphics 620| - |
| SSD | Crucial 1TB SSD| - |
| Screen | idk | - |
| Memory | 16GB LPDDR4 | - |
| Battery | idk | - |
| Camera | idk | - |
| Wi-Fi & BT | BCM4360 | - |
| Ports | 1 x USB3 Type-C/2 x USB 3/1 x USB 2/1 x Ethernet| - |
| Audio | idk |
# Working ✅
| Feature | Notes |
| --------- | ----------------------------------------------- | 
| Screen 🖥 | ✅ |
| Keyboard/TouchPad/Track Point⌨️| ✅ |
| USB-A / USB-C | ✅|
| Speaker/Hadphone jack 🔉| ✅ |
| Video Output | ✅ ,HDMI/USB-C |
| Sleep 🛏️ | ✅ |
| Internal Camera|✅|
| Handoff,AirDrop, Apple Watch unlock|✅|
| Internal microphone|✅|

# Known Issues ❓
| Feature | Notes |
| --------- | ----------------------------------------------- |
| Battery | ❓,I didn't patching it deeply, it should work|
| EC Control | ❓,Sometimes it will report EC error when power on, please try to unplug the power and try to lightly press the power button,No fix plan|
| F1-F3🔊,F5-F6🌞,F4,F7-F12 keys|❓,No fix plan|

# Not Working ❌
| Feature | Notes |
| --------- | ----------------------------------------------- |
| Apple Music Lossless / Apple TV / Disney+ |❌,DRM is broken for iGPU-only systems|


# Before Install
- Generate new SMBIOS https://github.com/corpnewt/GenSMBIOS
- The current wireless driver is not very stable, you may need to prepare a wired network (or try to add a wireless network manually during the installation)

# After Install
- Setting > TouchPad. Untick Force Click and haptic feedback this one causing invert click on touchpad

# Other Respositories

- x1c6-hackintosh <https://github.com/tylernguyen/x1c6-hackintosh>
- ThinkPad-X1C8-Hackintosh <https://github.com/HJebbour/ThinkPad-X1C8-Hackintosh>
- Lenovo-Y900x-Hackintosh <https://github.com/SukkaW/Lenovo-Y9000X-Hackintosh>

# Credits

- The guys from [Acidanthera](https://github.com/acidanthera) that make this possible
- [Apple](http://apple.com) for macOS