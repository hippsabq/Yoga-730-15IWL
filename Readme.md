# Yoga 730-15IWL

My laptop: 730-15IWL, i5-8265U (Whiskey Lake) with UHD 630 graphics. Using DW1560 \

This is a slight modification of DragonFlyLee's 730-13IKB Repo here ([https://github.com/dragonflylee/Yoga-730-hackintosh](https://github.com/dragonflylee/Yoga-730-hackintosh)). His repo works great on a 730-13IKB but the screen was incredibly dim on my system.

## BIOS Prep
-  Disable Secure Boot
-  Disable Intel SGX
-  Turn on ACHI

## Changes from DragonFlyLee's repo:
- removed SSDT-PNLF and added FixPNLF to config. Changes screen from incredibly dim to incredibly bright. Much brighter than the windows side will get...interesting.
- SMBIOS changed to MacBook Pro (13-inch, 2018, Four Thunderbolt 3 Ports)

## Things I'm working on
- Trying to figure out Thunderbolt and use with my eGPU (hotplug if capable)
- Adjust screen brightness to reasonable level
