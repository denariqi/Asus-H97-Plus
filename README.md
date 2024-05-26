# Asus-H97-Plus Hackintosh
- Mainboard: ASUS H97-Plus
- CPU: 4th Gen Intel(R) Core(TM) i5-4790
- RAM: DDR3 1600 16GB (8GB+8GB)
- GPU: AMD RX570 4G (Sapphire)
- LAN: RTL8111
- Wi-Fi: BCM94360CD
- Audio: ALC887
- Generic: MacPro7.1
- macOS: Monterey
- BASE EFI: OpencCore 8.6
# ACPI
- SSDT-EC-DESKTOP.aml
- SSDT-PLUG-DRTNIA.aml
# Drivers
- HfsPlus.efi
- OpenRuntime.efi
- ResetNvramEntry.efi
- ToggleSipEntry.efi
- OpenCanopy.efi
# Tools
- CFGLock.efi
- OpenShell.efi
- VerifyMsrE2.efi
# KextS
- Lilu
- VirtualSMC
  + SMCProcessor
  + SMCSuperIO
- WhateverGreen
- AppleALC
- NVMeFix
- RealtekRTL8111
- USBMapH97 (USBInjectAll)
- RestrictEvents
- AGPMInjector
- RadeonBoost
