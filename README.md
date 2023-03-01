# MSI_GS75_9Sx_EFI
Opencore to Hackintosh MSI GS-75-9SX laptops

Forked from gkShine/MSI_GS65_9SE_EFI. Modified to hackintosh MSI GS75-9Sx laptops

Tested on an GS75-9SF laptop

## Specs
- i7 9750H
- RTX 2070 maxq
- Samsung PM981 ( /!\ cannot install osx on this drive: You have to change the drive or add another one)
- Intel WiFi card
- Killer E2500 ethernet


## What works 

- Ethernet
- Wifi (Airportitwlm on Catalina & Monterey, itlwlm on Ventura)
- 240Hz with UHD 630 graphics, with acceleration
- Audio
- Sleep
- USB (at USB 3.0 speed)
- Keyboard Lighting

## What don't work

- Sometime, screen is black on boot
- RTX 2070 (get disabled on boot)
- External display (The hdmi and usb c ports are linked to the RTX card)
- Samsung PM981 NVME drive: known issue, so you have to change the drive


## What i'm not sure about

- Thunderbolt

## Installation 

Clone it or go to the realeases page and download the zip

Create a EFI folder on your EFI partition and put the contents