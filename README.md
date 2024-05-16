# ROG-STRIX-Z370-I-GAMING OpenCore
OpenCore for ASUS ROG STRIX Z370-I GAMING

# Version List
Versions, hardware, what works and what doesn't work or untested.

 1.0.1
-
Hardware tested:
Part|Model|Remarks
|-|-|-|
Motherboard|Asus Z370-I Gaming
CPU|i7-9700k
RAM|Corsair Vengeance Pro SL 2x16Gb 3600MHz
SSD|Corsair MP600 CORE XT 2x1Tb
GPU|Asus Dual RX 6600 XT|works with `agdpmod=pikera`
WiFi/BT|Fenvi BCM94360NG|requires OCLP on Sonoma

Not working / untested:
* Testing in progress

0.7.7
-
Hardware tested:
Part|Model|Remarks
|-|-|-|
Motherboard|Asus Z370-I Gaming|
CPU|i7-8700k|
RAM|Goodram 1x16Gb 2333MHz|
SSD|Kingston NV1 500Gb|
iGPU|UHD630|`igfxonln=1` for monitor wake up after sleep
WiFi/BT|Fenvi BCM94360NG|requires OCLP on Sonoma

Not working / untested:
* DRM (not tested, can be fixed by using dGPU)
* Integrated audio (I don't use, but it can be be easily fixed)
