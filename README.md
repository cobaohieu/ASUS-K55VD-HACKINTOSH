# ASUS-K55VD-HACKINTOSH install OS X 10.10 Yosemite, OS X 10.11 El Capital, macOS 10.12 Sierra
Make Laptop ASUS K55VD like Mac Book Pro 2013 run real macOS.

...............................................:System:...............................................

- Processor : Intel(R) Core(TM) i5-3210M CPU @ 2.50GHz (Ivy Bridge)
- Graphics Processor(GPU) : Intel HD4000 and Nvidia Optimus GT610M with 2GB DDR3 VRAM
- Hard disk : HDD Seagate 500GB
- RAM : 6GB DDR3 / bus 1600
- Wifi : Qualcomm Atheros AR9485WB-EG not work (Replaced by: AR9285)
- LAN : Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter
- Audio : Realtek ALC270
- USB 3.0 : Intel 7series/210 USB 3.0
 - Touchpad : Elan Touchpad
- Webcam : 0.3 Web Camera
- Card reader: Realtek PCI Express not work
- Monitor: 15.6" 16:9 HD (1366x768) LED Backlight
- Optical Drive: Super-Multi DVD (Optional).
    
...............................................:Status:...............................................

- Status Working:
  + Graphics (Intel HD4000)
  + Audio
  + WIFI (Replaced)
  + LAN
  + HDMI
  + VGA work but not good
  + Sleep, Processor Speedsteps and Native power management.
  + Trackpad
  + Fn Hotkeys
  + USB works
  + Disable turbo boost on battery (if neccessary)
    
- Status not working:
  + GT610M Graphics
  + Realtek CardReader
  + Webcam
  + WIFI (If not replaced)
    
...............................................:Prepair:...............................................

- One USB 3.0 with 8Gb or higher
- Sources OS: http://osx.vn/threads/tong-hop-link-download-macos-10-4-10-12-2-orginal-tu-mac-app-store.286
- Sources code Terminal: 
  + 10.10: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Guide%20Setup%20OS%20X%20Yosemite.txt 
  + 10.11: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Guide%20Setup%20OS%20X%20El%20Capital.txt 
  + 10.12: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Guide%20Setup%20macOS%20Sierra.txt
      (Please rename sources setup by copy sources setup to Application folder before run Terminal, rename UsbName to your usb name)
- Sources Clover: 
  + 10.10: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/10.10%20Clover.zip
  + 10.11: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/10.11%20Clover.zip
  + 10.12: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/10.12%20Clover.zip
- Sources Tool: Hackintosh Vietnam Tool V1.97 (if you install OS X 10.10 or 10.11, not working on 10.12)
- 30 minutes to setup or higher
- A PC run mac OS or virtual machine run on Windows 7 or higher
    
...............................................:Install:...............................................
- Seperate HDD with WindowsPE or Windows 7 or higher or source setup windows.
- Open Command Prompt via Aministrator access and typing.
  + diskpart
  + list disk (please choose your HDD you want install macOS)
  + sel disk 0 (change 0 to your HDD on list)
  + create part efi size=504 (if no empty partition please delete about 50Gb)
  + format fs=fat32 quick label="EFI"
  +create part primary size=48500 (change 48,50Gb to your Gb you want to create, if you want create all please delete size=48500)
  + format fs=exfat quick label="Macintosh HD"
  + Done.
  
- Plug in usb to usb 3.0 port and Format usb with 2 partition: 1Gb for "ESP" with Fat and the rest Gb for UsbName with HFS+ (notes: Format with GUID Partition MAP)
- Download source setup and copy it to Application folder
- Download and open file sources code ".txt" for Terminal which OS you want to setup
- Open Terminal and copy and paste from first line to final line.
-  After it all, copy Clover folder go to Volume Fat of USB like "ESP" (if can't boot please remove folder APPLE) (Or you can copy folder to Volume EFI on HDD and create boot from BIOS)
- Done. Reboot and Press ESC to choose boot (please choose first line: "UEFI USB....").
-  After boot please choose Continue > Agree > Agree > choose your volume to install (Look in menu bar and choose Utilities > Disk Utility > Choose your label volume "Macintosh HD" or your volume name and Earse with HFS+) like "Macintosh HD" > Install > Done. Wait for a few minutes your laptop will reboot.
- After reboot: Choose your country > keyboard > Choose your network > Transfer do not > Enable Location > Login icloud (if you need or skip) > Agree with Term and Condition > Create your account and set time zone > Diagnostic & Usage > Done.
- Modify OS
    - If you have a bios boot with EFI folder on volume EFI like up you don't want to make it again.
    - If you not please do it below.
    - Go to BIOS set up > Boot > look below Add new boot option > Add boot option: macOS Boot Manager > Select Filesystems: Choose your HDD contain volume Mackintosh HD > Patch for boot option: \EFI\CLOVER\CLOVERX64.efi > create. Please choose it to first boot.
    - Done. Go to your Macintosh HD and enjoy. Install your software you like or love.
    
.............................................Thanks for sites and guys.............................................
- 1. BetaDroid: https://github.com/BetaDroid
- 2. RehabMan: https://github.com/RehabMan
- 3. vit9696: https://github.com/vit9696
- 4. Github: https://github.com
- 5. Google: https://youtube.com/southernvevo
- 6. Facebook: https://www.facebook.com/southernvevo
- 7. Tonymacx86.com http://tonymacx86.com
- 8. Macintosh-VN http://macintosh.vn
- 9. OSX.vn: http://osx.vn
...........................................Thanks for visting and watching..........................................

