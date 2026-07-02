# Dell-Latitude-3490-i5-7200u-Hackintosh

This EFI was custom made for my specific needs and variant of the Dell Latitude 3940, beware that it won’t work with other variantes, like the ones with the 8th Gen CPUs, I still recommend you to made you own EFI!

First of all, I would like to thank the Reddit user “misterflo” for posting about a successful Monterrey install in the 3490, GitHub user “huburtx” for posting his Big Sur OpenCore EFI, and everyone that took part on the development of OpenCore and all the Drivers, Kexts and Patches that made this possible, and, of course, Dortania Guide that allowed a newbie like me to pull this of, you guys are awesome.

## I`M NOT RESPONSIBLE FOR ANY DAMAGE TO YOUR LAPTOP,  DO AT YOUR OWN RISK

## System Specifications

Brand: Dell
Model: Latitude 3490
CPU: Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz
GPU:  Intel Corporation HD Graphics 620 (rev 02)
RAM: 16 GB at 2133 Ghz ( 2x 8GB SO-DIMM)
MOBO: OEM Dell
SSD: ADATA SU810NS38 256GB (Elementary OS 8) / SanDisk SSD PLUS 240GB (MacOS Ventura)
AUDIO CODEC: ALC3246 Analog
ETHERNET:  RTL8111/8168/8211/8411
WIFI/BT CARD: QCA6174 802.11ac Wireless Network Adapter
KEYBOARD / TOUCHPAD: I2C

## EFI Specifications

OpenCore Version: 1.0.7 (RELEASE/DEBUG)
ACPIs: Dortania’s Prebuild
Drivers: Dortania’s indications + Fix for dual SSD
Kexts: Dortania’s indications + USB Tethering, Display Brightness, Custom USB Map, Touchpad FIX
Max MacOS Versions: Ventura
Apple Device: MacBook Pro 13-inch 2017

## WHAT WORKS

Screen
Keyboard / Touchpad (Needs to fix some settings to improve usage)
Block / Sleep
Sound ( Internal Mic + Speaker)
Brightness Control (After fixing short keys) 
Internet via Ethernet
Internet via USB Tethering (Android)
Wifi ( Using a External USB Wifi Adapter TP-LINK TL-WN75NV1 + Chris11 Driver)
Mac OS Ventura works more or less normally

## WHAT DON`T WORK

Bluetooth  / AirDrop (Incompatible wifi card, you can change to a compatible one, but, you will need to add some other kexts)
External Mic or Headset (This I don’t really know why, didn’t bother to fix because I use MacOS only to to work in this laptop, and Elementary OS for Gaming, there this works)
MacOS Macbook specific features like some touchpad gestures

## FILES

EFI_INSTALL_ORIGINAL - The EFI I used to first install MacOS in the SSD, it’s based on the DEBUG version of OpenCore, so, verbose and Logs are enabled, and it’s missing some post install fixes, I strongly recommend you to use this one for the installation

EFI_V0.9 - The final, polished EFI with all the fixes and optimizations, Graphical Boot, without  Verbose or Logs, change to this one after installation

## TIPS

Spend some time in the BIOS and change everything that Dortania’s Guide ask you to do
If you plan to Dual boot, aways uses different SSDs for MacOS and the Other OS, beware to create a custom boot sequence and, especially with a ubuntu based linux distro, have your EFI files in both SSDS.

## BONUS

Tell me if you have any questions and tell me if it was useful for you :)  
