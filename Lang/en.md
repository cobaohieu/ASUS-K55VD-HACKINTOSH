# How to install OS X 10.10 Yosemite, OS X 10.11 El Capital, macOS 10.12 Sierra, macOS High Sierra 10.13 on Laptop ASUS K55VD

Make Laptop ASUS K55VD like Mac Book Pro 2012 late run real macOS.
This is a working set of kexts and configurations for running OS X, macOS for laptop ASUS K55VD.


## System
### Specifications:
  - Processor : Intel(R) Core(TM) i5-3210M CPU @ 2.50GHz (Ivy Bridge)
  - Graphics Processor(GPU) : Intel HD4000 and Nvidia Optimus GT610M with 2GB DDR3 VRAM
  - Hard disk : HDD Seagate 500GB
  - RAM : 6GB DDR3 / bus 1600
  - Wifi : Qualcomm Atheros AR9485WB-EG
  - LAN : Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter
  - Audio : Realtek ALC270
  - USB 3.0 : Intel 7series/210 USB 3.0
  - Touchpad : Elan Touchpad
  - Webcam : 0.3 Web Camera
  - Card reader: Realtek PCI Express
  - Monitor: 15.6" 16:9 HD (1366x768) LED Backlight
  - Optical Drive: Super-Multi DVD (Optional).

## Status
### Status Working:
  - Graphics (Intel HD4000).
  - Audio.
  - WIFI.
  - Bluetooth.
  - Webcam.
  - LAN.
  - HDMI.
  - VGA work but not good.
  - Sleep, Processor Speedsteps and Native power management.
  - Trackpad.
  - Fn Hotkeys.
  - USB works.
  - Disable turbo boost on battery (if neccessary).

### Status not working:
  - GT610M Graphics
  - Realtek CardReader (Sometimes work, sometimes not work)
 
## Prepair
  - One USB 3.0 with 8Gb or higher

### Sources OS:
     https://pastebin.com/fubebWzy

### Sources code Terminal:
   - 10.10: <a href="https://raw.githubusercontent.com/southernvevo/ASUS-K55VD-HACKINTOSH/master/Command%20Prompt/Guide%20Setup%20OS%20X%20Yosemite%2010.10.txt">Guide Setup OS X Yosemite 10.10</a>
   - 10.11: <a href="https://raw.githubusercontent.com/southernvevo/ASUS-K55VD-HACKINTOSH/master/Command%20Prompt/Guide%20Setup%20OS%20X%20El%20Capital%2010.11.txt">Guide Setup OS X El Capital 10.11</a>
   - 10.12: <a href="https://raw.githubusercontent.com/southernvevo/ASUS-K55VD-HACKINTOSH/master/Command%20Prompt/Guide%20Setup%20macOS%20Sierra%2010.12.txt">Guide Setup macOS Sierra 10.12</a>
   - 10.13: <a href="https://raw.githubusercontent.com/southernvevo/ASUS-K55VD-HACKINTOSH/master/Command%20Prompt/Guide%20Setup%20macOS%20High%20Sierra%2010.13.txt">Guide Setup macOS High Sierra 10.13</a>
   - 10.14: <a href="https://raw.githubusercontent.com/southernvevo/ASUS-K55VD-HACKINTOSH/master/Command%20Prompt/Guide%20Setup%20macOS%20Mojave%2010.14.txt">Guide Setup macOS Mojave 10.14</a>
  - (Please rename sources setup by copy sources setup to Application folder before run Terminal, rename UsbName or Usb or Usbmac to your usb name)

### Sources Clover: (Please choose your version of mac OS or OS X you want to install on my Laptop)
  - 10.10: <a href="/10.10.5">Click here move to folder.</a>
  - 10.11: <a href="/10.11.6">Click here move to folder.</a>
  - 10.12: <a href="/10.12.6">Click here move to folder.</a>
  - 10.13: <a href="/10.13.6">Click here move to folder.</a>
  - 10.14: <a href="/10.14">Click here move to folder.</a>

### Sources Sofware:
  - Link download: <a href="/Software">Click here move to folder.</a>
  - 30 minutes to setup or higher.
  - A PC run mac OS or virtual machine run on Windows 7 or higher.


## DOWNLOAD: PLEASE CHECK MY RELEASES.

   https://github.com/southernvevo/ASUS-K55VD-HACKINTOSH/releases/

 
## Install
  - Seperate HDD with WindowsPE or Windows 7 or higher or source setup windows.
  - Open Command Prompt via Aministrator access and typing.
    - diskpart
    - list disk | (please choose your HDD you want install macOS).
    - sel disk 0 | (change 0 to your HDD on list).
    - create part efi size=504 | (if no empty partition please delete about 50Gb).
    - format fs=fat32 quick label="EFI"
    - create part primary size=48500 | (change 48,50Gb to your Gb you want to create, if you want create all please delete size=48500, with mac 48,50Gb = 50Gb).
    - format fs=exfat quick label="Macintosh HD"
    - exit
  - Done. 

  **&nbsp;**

     https://www.youtube.com/watch?v=uPbyxqggrA8

  - Plug in usb to usb 3.0 port and Format usb  with HFS - (notes: Format with GUID Partition MAP).
  - Download source setup and copy it to Application folder.
  - Download and open file sources code ".txt" for Terminal which OS you want to setup.
  - Open Terminal and copy and paste from first line to final line.
  -  After it all, copy Clover folder go to Volume Fat32 of EFI | (if can't boot please remove folder APPLE).
  - Make USB Boot on mac OS or OS X or virtual machine run mac OS or OS X | (Or you can copy folder to Volume EFI on HDD and create boot from BIOS).

  **&nbsp;**

     https://youtu.be/9GjaZQTLVeQ

  - Setup

  **&nbsp;**

     https://youtu.be/7gG6liug2w8

  -  After boot please choose Continue > Agree > Agree > choose your volume to install | (Look in menu bar and choose Utilities > Disk Utility > Choose your label volume "Macintosh HD" or your volume name and Earse with HFS - for HDD or AFPS for SSD) like "Macintosh HD" > Install > Done. Wait for a few minutes your laptop will reboot.
  - After reboot: Choose your country > keyboard > Choose your network > Transfer do not > Enable Location > Login icloud (if you need or skip) > Agree with Term and Condition > Create  your account and set time zone > Diagnostic & Usage > Done.

#### Modify OS
  - Generator SSDT for CPU 

  **&nbsp;**

     https://youtu.be/wSqNAt8mHGE
     
  - Fix WiFi woking on mac OS 

  **&nbsp;**

     https://youtu.be/JU6qUJ-MpA0

  - Install Clover EFI Bootloader 

  **&nbsp;**

     https://www.youtube.com/watch?v=W5pLM5bKfaA

  - Fix Graphics with Night Mode, True HD display

  **&nbsp;**

     https://youtu.be/8XlJ8UN94H

  - Install some kext to fix mute after lid your Laptop and view infomation for app HWMonitor 

  **&nbsp;**

     https://youtu.be/kXXDElK2EA8   

  - If you have a bios boot with EFI folder on volume EFI like up you don't want to make it again.
  - If you not please do it below.
  - Go to BIOS set up > Boot > look below Add new boot option > Add boot option: macOS Boot Manager > Select Filesystems: Choose your HDD contain volume Mackintosh HD > Patch for boot option: \EFI\CLOVER\CLOVERX64.efi > create. 
  - Please choose it to first boot.
  - Done. Go to your Macintosh HD and enjoy. Install your software you like or love.






