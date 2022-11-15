# Ryzentosh EFI Folder (OC Edition)
###### Ryzentosh EFI Setup for my main pc
- Has been tested and works on macOS Catalina 10.15.7, macOS Big Sur 11.4 and macOS Monterey beta 1.
- Works alongside other OS'S
- Graphics acceleration works
- Audio and Microphone works
- Ethernet works
- iCloud, iMessage and another services work
- Works with pretty much any Zen processor
- Will this work on macOS Monterey?
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
- SSDT-EC-USBX-DESKTOP
- HfsPlus
- OpenRuntime
- OpenCanopy

# Sources and Utilities used
- [Dortania's OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [khronokernel's Vanilla Guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/)
- [ProperTree](https://github.com/corpnewt/ProperTree)
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
- [SanityChecker](https://opencore.slowgeek.com/)
- [AMD Kernel Patches](https://github.com/AMD-OSX/AMD_Vanilla/tree/opencore)
# What's new with this ryzentosh install?
- Well it doesn't use clover bootloader anymore lol.
- Replaced Ryzen 5 2600X with Ryzen 7 3700X


# Notes
- AMD supported cpu's below
  - Zen
  - Threadripper
  - Jaguar
  - Bulldozer

- Intel supported cpu's below
  - Ivy Bridge
  - Ivy Bridge E
  - Sandy Bridge
  - Sandy Bridge E
  - Haswell
  - Skylake
  - Kaby Lake
  - Coffee Lake
  - Coffee Lake Plus
  - Whiskey Lake
  - Comet Lake
  - Ice Lake
  - Haswell-E
  - Broadwell-E
  - Skylake-X
  - Skylake-W
  - Cascade Lake X
  - Cascade Lake W
  - Penryn
  - Nehalem
  - Westmere
  - 
  - Clarkdale
  - Arrandale
