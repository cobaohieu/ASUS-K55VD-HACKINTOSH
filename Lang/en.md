# ASUS-K55VD-HACKINTOSH install OS X 10.10 Yosemite, OS X 10.11 El Capital, macOS 10.12 Sierra, macOS High Sierra 10.13
Make Laptop ASUS K55VD like Mac Book Pro 2012 late run real macOS.

<img class="alignnone size-full wp-image-486 alignright" src="https://viethackintosh.com/wp-content/uploads/2017/03/ASUS2.jpg" alt="" width="960" height="539"/>
...............................................:System:...............................................
</strong>
<br>
<strong>
	- Specifications:
</strong>
<br>
+ Processor : Intel(R) Core(TM) i5-3210M CPU @ 2.50GHz (Ivy Bridge)
<br>
+ Graphics Processor(GPU) : Intel HD4000 and Nvidia Optimus GT610M with 2GB DDR3 VRAM
<br>
+ Hard disk : HDD Seagate 500GB
<br>
+ RAM : 6GB DDR3 / bus 1600
<br>
+ Wifi : Qualcomm Atheros AR9485WB-EG
<br>
+ LAN : Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter
<br>
+ Audio : Realtek ALC270
<br>
+ USB 3.0 : Intel 7series/210 USB 3.0
<br>
+ Touchpad : Elan Touchpad
<br>
+ Webcam : 0.3 Web Camera
<br>
+ Card reader: Realtek PCI Express
<br>
+ Monitor: 15.6" 16:9 HD (1366x768) LED Backlight
<br>
+ Optical Drive: Super-Multi DVD (Optional).
<br>
<br>
<strong>
	...............................................:Status:...............................................
</strong>
<br>
<strong>
- Status Working:
</strong>
<br>
  + Graphics (Intel HD4000)
<br>
  + Audio
<br>
  + WIFI
<br>
  + Bluetooth
<br>
  + Webcam
<br>
  + LAN
<br>
  + HDMI
<br>
  + VGA work but not good
<br>
  + Sleep, Processor Speedsteps and Native power management.
<br>
  + Trackpad
<br>
  + Fn Hotkeys
<br>
  + USB works
<br>
  + Disable turbo boost on battery (if neccessary)
<br>
<br>
<strong>
- Status not working:
</strong>
<br>
  + GT610M Graphics
<br>
  + Realtek CardReader
<br> 
<br>
<strong>
	...............................................:Prepair:...............................................
</strong>
<br>
- One USB 3.0 with 8Gb or higher
<br>
- Sources OS: <a href="https://drive.google.com/drive/folders/0B0uxYlh9Q2lTc0NfbFBYUDI3T2s?usp=sharing">Google Drive</a>
<br>
- Sources code Terminal: 
<br>
  + 10.10: <a href="/Command Prompt/Guide Setup OS X Yosemite 10.10.txt">Guide Setup OS X Yosemite 10.10</a>
<br>
  + 10.11: <a href="/Command Prompt/Guide Setup OS X El Capital 10.11.txt">Guide Setup OS X El Capital 10.11</a>
<br>
  + 10.12: <a href="/Command Prompt/Guide Setup macOS Sierra 10.12.txt">Guide Setup macOS Sierra 10.12</a>
<br>
- Sources code Terminal: 
  + 10.13: <a href="/Command Prompt/Guide Setup macOS High Sierra 10.13.txt">Guide Setup macOS High Sierra 10.13</a>
<br>
  + (Please rename sources setup by copy sources setup to Application folder before run Terminal, rename UsbName to your usb name)
<br>
- Sources Clover: (Please choose your version of mac OS or OS X you want to install on my Laptop)
<br>
  + 10.10: 
<br>
  + 10.11: 
<br>
  + 10.12: 
<br>
  + 10.13: 
<br>
- Sources Sofware: 
<br>
  + Link download: <a href="/Software">Click here move to folder</a>
<br>
- 30 minutes to setup or higher
<br>
- A PC run mac OS or virtual machine run on Windows 7 or higher
<br>
<br> 
<strong>
	...............................................:Install:...............................................
</strong>
<br>
- Seperate HDD with WindowsPE or Windows 7 or higher or source setup windows.
<br>
- Open Command Prompt via Aministrator access and typing.
<br>
  + diskpart
<br>
  + list disk (please choose your HDD you want install macOS)
<br>
  + sel disk 0 (change 0 to your HDD on list)
<br>
  + create part efi size=504 (if no empty partition please delete about 50Gb)
<br>
  + format fs=fat32 quick label="EFI"
<br>
  +create part primary size=48500 (change 48,50Gb to your Gb you want to create, if you want create all please delete size=48500, with mac 48,50Gb = 50Gb)
<br>
  + format fs=exfat quick label="Macintosh HD"
<br>
  + Done. 
<br>
<h4><a href="https://www.youtube.com/watch?v=uPbyxqggrA8">Click here to view Videos</a></h4>
<br>
- Plug in usb to usb 3.0 port and Format usb  with HFS+ (notes: Format with GUID Partition MAP)
<br>
- Download source setup and copy it to Application folder
<br>
- Download and open file sources code ".txt" for Terminal which OS you want to setup
<br>
- Open Terminal and copy and paste from first line to final line.
<br>
-  After it all, copy Clover folder go to Volume Fat32 of EFI
<br>
(if can't boot please remove folder APPLE) 
<br>
- Make USB Boot on mac OS or OS X or virtual machine run mac OS or OS X <h4><a href="https://youtu.be/9GjaZQTLVeQ">Click here to view Videos</a></h4>
<br>
(Or you can copy folder to Volume EFI on HDD and create boot from BIOS)
<br>
-  After boot please choose Continue > Agree > Agree > choose your volume to install 
<br>
	(Look in menu bar and choose Utilities > Disk Utility > Choose your label volume "Macintosh HD" or your volume name and Earse with HFS+ for HDD or AFPS for SSD) 
<br>
	like "Macintosh HD" > Install > Done. Wait for a few minutes your laptop will reboot.
<br>
- After reboot: Choose your country > keyboard > Choose your network > Transfer do not > Enable Location > Login icloud (if you need or skip) > Agree with Term and Condition > Create your account and set time zone > Diagnostic & Usage > Done.
<br>
- Modify OS
<br>
    - Generator SSDT for CPU <h4><a href="https://youtu.be/wSqNAt8mHGE">Click here to view Videos</a></h4>
<br>
    - Fix WiFi woking on mac OS <h4><a href="https://youtu.be/JU6qUJ-MpA0">Click here to view Videos</a></h4>
<br>
    - Install Clover EFI Bootloader <h4><a href="https://www.youtube.com/watch?v=W5pLM5bKfaA">Click here to view Videos</a></h4>
<br>
    - Fix Graphics with Night Mode, True HD display <h4><a href="https://youtu.be/8XlJ8UN94Ho">Click here to view Videos</a></h4>
<br>
    - Install some kext to fix mute after lid your Laptop and view infomation for app HWMonitor <h4><a href="https://youtu.be/kXXDElK2EA8">Click here to view Videos</a></h4>
<br>
    - If you have a bios boot with EFI folder on volume EFI like up you don't want to make it again.
<br>
    - If you not please do it below.
<br>
    - Go to BIOS set up > Boot > look below Add new boot option > Add boot option: macOS Boot Manager > Select Filesystems: Choose your HDD contain volume Mackintosh HD > Patch for boot option: \EFI\CLOVER\CLOVERX64.efi > create. 
<br>
	- Please choose it to first boot.
<br>
    - Done. Go to your Macintosh HD and enjoy. Install your software you like or love.
<br>
<br>
<strong>
	.............................................Thanks for sites and guys.............................................
</strong>
<br>
- 1. BetaDroid: https://github.com/BetaDroid
<br>
- 2. RehabMan: https://github.com/RehabMan
<br>
- 3. vit9696: https://github.com/vit9696
<br>
- 4. Github: https://github.com
<br>
- 5. Google: https://youtube.com/southernvevo
<br>
- 6. Facebook: https://www.facebook.com/southernvevo
<br>
- 7. Tonymacx86.com http://tonymacx86.com
<br>
- 8. Macintosh-VN http://macintosh.vn
<br>
- 9. OSX.vn: http://osx.vn
<br>
- 10. Viethackintosh: https://viethackintosh.com/
<br>
- 11. Weloveapple: https://weloveapple.vn/
<br>
<br>
<strong>
	...........................................Thanks for visting and watching..........................................
</strong>
<img class="alignnone size-full wp-image-487" src="Images/img10131.png" alt="" width="960" height="539" />

