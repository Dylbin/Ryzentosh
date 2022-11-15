# Ryzentosh EFI Folder (OC Edition)
###### Ryzentosh EFI Setup for my main pc
- Has been tested and works on macOS Catalina 10.15.7, macOS Big Sur 11.4 and macOS Monterey beta 1.
- Works alongside other OS'S
- Graphics acceleration works
- Audio and Microphone works
- Ethernet works
- iCloud, iMessage and another services work
- Will this work on macOS Monterey and macOS Ventura?
  - Yes it does if you switch SmallTreeIntel82576.kext with ApplelGB.kext

# Short PC Specifications
- Radeon RX 5700 XT
- Ryzen 5 3700X 8-Core
- ASUS Rog Strix B450-F Gaming

# Kext List
- AMDRyzenCPUPowerManagement
- AppleALC (For Audio)
- Lilu (Graphics)
- WhateverGreen (Graphics)
- RadeonBoost
- SmallTreeIntel82576 (Ethernet)
- SMCAMDProcessor
- VirtualSMC

# Drivers and other Modules
- SSDT-EC-USBX-DESKTOP.aml (Pre-Built)
- HfsPlus
- OpenRuntime
- OpenCanopy

# Sources and Utilities used
- [Dortania's OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [khronokernel's Vanilla Guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/)
- [ProperTree](https://github.com/corpnewt/ProperTree)
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
- [AMD Kernel Patches](https://github.com/AMD-OSX/AMD_Vanilla/tree/opencore)

# What's new with this ryzentosh install?
- Utilizes OpenCore bootloader instead of Clover bootloader.
- Replaced Ryzen 5 2600X with Ryzen 7 3700X
