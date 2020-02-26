{\rtf1\ansi\ansicpg1252\cocoartf2511
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Yoga 730-15IWL\
\
My laptop: 730-15IWL, i5-8265U (Whiskey Lake) with UHD 630 graphics. Using DW1560 \
\
This is a slight modification of DragonFlyLee's 730-13IKB Repo here ([https://github.com/dragonflylee/Yoga-730-hackintosh](https://github.com/dragonflylee/Yoga-730-hackintosh)). His repo works great on a 730-13IKB but the screen was incredibly dim on my system.\
\
## BIOS Prep\
-  Disable Secure Boot\
-  Disable Intel SGX\
-  Turn on ACHI\
\
## Changes from DragonFlyLee's repo:\
- removed SSDT-PNLF and added FixPNLF to config. Changes screen from incredibly dim to incredibly bright. Much brighter than the windows side will get...interesting.\
- SMBIOS changed to MacBook Pro (13-inch, 2018, Four Thunderbolt 3 Ports)\
- \
\
## Things I'm working on\
- Trying to figure out Thunderbolt and use with my eGPU (hotplug if capable)\
- Adjust screen brightness to reasonable level\
}