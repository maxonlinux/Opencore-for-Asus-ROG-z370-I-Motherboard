# ROG-STRIX-Z370-I-GAMING OpenCore
OpenCore for ASUS ROG STRIX Z370-I GAMING

# Version List
Versions, hardware, what works and what doesn't work or untested.

 1.0.1 v2
-
Release - https://github.com/maxonlinux/Opencore-for-Asus-ROG-z370-I-Gaming-Motherboard/releases/tag/1.0.1-v2

System version:

OS|Version|Number
|-|-|-|
|Sonoma|13.6.7|(22G720)|

Hardware tested:
Part|Model|Remarks
|-|-|-|
Motherboard|Asus Z370-I Gaming
CPU|i7-9700k
RAM|Corsair Vengeance Pro SL 2x16Gb 3600MHz
SSD|Corsair MP600 CORE XT 2x1Tb
iGPU|HD Graphics UHD630
dGPU|Asus Dual RX 6600 XT|`agdpmod=ingore` to get display out
WiFi/BT|Fenvi BCM94360NG|requires OCLP on Sonoma

Not working / untested:
* Everything works
* STRONGLY RECOMMENDED TO MAKE YOUR OWN USB MAP

 1.0.1
-
Release - https://github.com/maxonlinux/Opencore-for-Asus-ROG-z370-I-Gaming-Motherboard/releases/tag/1.0.1

Hardware tested:
Part|Model|Remarks
|-|-|-|
Motherboard|Asus Z370-I Gaming
CPU|i7-9700k
RAM|Corsair Vengeance Pro SL 2x16Gb 3600MHz
SSD|Corsair MP600 CORE XT 2x1Tb
iGPU|HD Graphics UHD630
dGPU|Asus Dual RX 6600 XT|`agdpmod=pikera` to get display out
WiFi/BT|Fenvi BCM94360NG|requires OCLP on Sonoma

Not working / untested:
* Testing in progress


0.7.7
-
Release - https://github.com/maxonlinux/Opencore-for-Asus-ROG-z370-I-Gaming-Motherboard/releases/tag/0.7.7

Hardware tested:
Part|Model|Remarks
|-|-|-|
Motherboard|Asus Z370-I Gaming|
CPU|i7-8700k|
RAM|Goodram 1x16Gb 2333MHz|
SSD|Kingston NV1 500Gb|
iGPU|HD Graphics UHD630|`igfxonln=1` for monitor to wake up after sleep
WiFi/BT|Fenvi BCM94360NG|requires OCLP on Sonoma

Not working / untested:
* DRM (not tested, can be fixed by using dGPU)
* Integrated audio (I don't use, but it can be be easily fixed)
