# OpenCore - High Sierra - Gigabyte Z390 Gaming M - i9 9900K + Nvidia GTX 1080
This is my Opencore 0.6.0 configuration for running macOS High Sierra with an i9 9900K, Gigabyte Gaming M Motherboard and Nvidia GTX 1080 Founder's Edition.
Gigabyte GC-Titan Ridge included but only seems to work for USB-C devices currently and is WIP to fix it.

Working:
Ethernet
Metal support in FCP
iMessage
USB-C devices via thunderbolt card

Not working:
Thunderbolt devices
Wifi / Bluetooth (no card, yet)

Notes: currently using DEBUG kexts and opencore, WIP to switch over to RELEASE to speed up booting. Didn't build a custom SSDT DSDT yet either.
