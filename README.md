# EFI-x79-Catalina-MacOs

## 🚀 Computer Characteristics

- Motherboard x79 Huananzhi (any manufacturer works)
- Processor xeon e5-2650v2 
- Memory ddr3 24GB (testing with Memory ECC and No ECC) 
- GPU RX 570 2048sp (if you have another model of the navi series, then add the following argument in bootargs "agdpmod=pikera"). more information in https://dortania.github.io/GPU-Buyers-Guide/misc/bootflag.html

## 📦 Working 
- Facetime
- Usb Ports
- Ethernet
- Wifi and Bluetooth (with models Fevi)
- Multi Monitor

## ✖️📦 NOT Working 
- Audio by Jack connector

## Necessary programs
- Explorer++ https://explorerplusplus.com/
- BalenaEtcher https://etcher.balena.io/
- miniTool Partion Wizard Free https://www.partitionwizard.com/

## Intructions
 1.- Download image vanilla Catalina from Olarilla page 
 2.- With BalenaEtcher flash image in usb 16gb
 3.- Open minitool Partion Wizard -> search your USB -> Select the partition call EFI (Fat32) -> click right and change the Letter -> Select any letter and click in Aply
 4.- Open Explorer++ like Administrator and seach your USB call EFI, delete folder EFI and replace with the folder EFI from this github
 5.- Configuration your bios https://dortania.github.io/OpenCore-Install-Guide/config-HEDT/ivy-bridge-e.html#intel-bios-settings
 6.- Install catalina in your Computer
 
