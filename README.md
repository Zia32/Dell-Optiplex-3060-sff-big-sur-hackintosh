# Dell-Optiplex-3060-sff-big-sur-hackintosh

Hi, I have installed Macos Big sur on my dell optiplex 3060 sff.

![Screenshot 2021-04-26 at 4 36 00 AM](https://user-images.githubusercontent.com/63354754/116013349-3b247300-a649-11eb-8696-e9fb01824b8f.png)

**Note:This guide does need some past experiance regarding hackintosh**

## Requirments
* One working MAC OS X Enviroment
* 16GB USB Stick (a larger drive may not bootable and/or require advanced partitioning)
* MacOS BigSur 11.0 installation file from the app store (redownload, just in case)
* Knowledge of editing PLIST files
* Some time

## Specs
* Proccessor
  * Intel Core i5-8500 3.0GHz
* RAM
  * 8gb DDR4 2666 MHz
* Sound Adapter
  * Realtek ALC 255
* Ethernet
  * Realtek RTL8111

## Bios Settings
* Enable:
  * SATA Operation : AHCI
  * Integrated NIC : Enable
  * Fastboot : Thorough

* Disable:
  * Secure Boot
  * Intel SGX

## Whats Works
Each and every thing works except Sleep. You will need a compatible wifi card for Wifi and Bluetooth. You can also use Ethernet or USB Wifi Dongle for Wifi.

## Installation Process
* Make a Big Sur bootable usb
* Mount the efi partition and paste my given EFI folder
* Then regenerate the Smbios in Plist
* Now boot the usb and install the OS
