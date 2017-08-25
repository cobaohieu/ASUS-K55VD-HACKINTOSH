# ASUS-K55VD-HACKINTOSH install OS X 10.10 Yosemite, OS X 10.11 El Capital, macOS 10.12 Sierra
Make Laptop ASUS K55VD like Mac Book Pro 2013 run real macOS.

<img class="alignnone size-full wp-image-486 alignright" src="https://viethackintosh.com/wp-content/uploads/2017/03/ASUS2.jpg" alt="" width="960" height="539"/>
<strong>Mọi người thông cảm do hiện tại cáp quang đang đứt và một số việc học hành còn dang dở, và một macOS 10.12.4 mới cập nhật nên mình sẽ cập nhật thường xuyên thêm</strong>
<h3 style="text-align: center">..............................................................................................</h3>
<h3 style="text-align: center"><strong>Vietnamese Ver: Updated soon</strong>
Hướng dẫn để cài đặt macOS Sierra 10.12.4 trên Laptop ASUS K55VD.</h3>
<strong>Cấu hình cơ bản:</strong>
◦ Processor : Intel(R) Core(TM) i5-3210M CPU @ 2.50GHz (Ivy Bridge)
◦ Graphics Processor(GPU) : Intel HD4000 and Nvidia Optimus GT610M with 2GB DDR3 VRAM
◦ Hard disk : HDD Hitachi 500GB
◦ RAM : 6GB DDR3 / bus 1600
◦ Wifi + Buetooth: Qualcomm Atheros AR9485WB-EG
◦ LAN : Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter
◦ Audio : Realtek ALC270
◦ USB 3.0 : Intel 7 series/210 USB 3.0
◦ Touchpad : Elan Touchpad
◦ Webcam : 0.3 Web Camera
◦ Card reader : Realtek PCI Express not work
◦ Monitor: 15.6" 16:9 HD (1366x768) LED Backlight
◦ Optical Drive: Super-Multi DVD (Optional) 

<strong>Các thành phần hoạt động tốt:</strong>
◦ Graphics (Intel HD4000)
◦ Audio
◦ WIFI + Bluetooth
◦ LAN
◦ Webcam
◦ HDMI
◦ VGA
◦ Sleep, Processor Speedsteps and Native power management.
◦ Trackpad cảm ứng đa điểm 4 ngón
◦ Fn Hotkeys
◦ USB works
◦ Realtek CardReader
◦ Disable turbo boost on battery

<strong>Các thành phần không hoạt động:</strong>
◦ GT610M Graphics

<strong>Yêu cầu:</strong>
◦ BIOS cài về mặc định: khởi động máy tính F2 &gt; F9 &gt; F10 &gt; Enter.
◦ Một USB 3.0 8Gb hoặc cao hơn.
◦ Sources OS link download: <a href="https://www.fshare.vn/file/AH8IJYXJJVGD" target="_blank">Fshare</a>
◦ Một folder Clover EFI (DSDT, SSDT và tất cả các kext gơm lượm): <a href="https://github.com/southern21/ASUS-K55VD-HACKINTOSH" target="_blank">GitHub</a>
◦ Kext Network active Wi-Fi 9485 &amp; Graphics active Night Shift: <a href="https://github.com/southern21/ASUS-K55VD-HACKINTOSH" target="_blank">GitHub</a>
◦ Folder Tools &amp; Software: <a href="https://drive.google.com/drive/folders/0B_rOF-XuryyyR2c0STJKV3dwanc?usp=sharing" target="_blank">Google Drive</a>
◦ Kext Utility V2.6.6 <a href="https://cvad-mac.narod.ru/files/Kext_Utility.app.v2.6.6.zip" target="_blank">Cvad-mac.narod.ru/</a>
◦ Link Download MiniTool Partition Wizard Free Edition 10.2: <a href="https://download3.minitool.com/pw10/pw10-free.exe" target="_blank">Partitionwizard.com</a>
◦ Folder Chứa các lệnh Terminal Prompt: <a href="https://github.com/southern21/ASUS-K55VD-HACKINTOSH" target="_blank">GitHub</a>
◦ 30 – 40 phút cài đặt.
◦ Mình cài trên HDD chuẩn EFI nhé
◦ Một Laptop chạy Windows 7 hoặc cao hơn

<strong>Phân vùng ổ cứng hệ thống</strong>
[embed]https://www.youtube.com/watch?v=uPbyxqggrA8[/embed]

◦ Tạo bộ cài đặt trên USB
[embed]https://www.youtube.com/watch?v=P_O1PTPiQok[/embed]


◦ Cài đặt macOS trên HDD:
[embed]https://www.youtube.com/watch?v=P930Yx31GrU[/embed]


◦ Hoàn thiện máy sau cài đặt:
[embed]https://www.youtube.com/watch?v=XasTaBiUNWk[/embed]


Khởi động lại và xem kết quả và test lại toàn bộ hệ thống xem đã hoàn chỉnh chưa?

<img class="alignnone size-full wp-image-562" src="https://viethackintosh.com/wp-content/uploads/2017/03/Screen-Shot-2017-04-04-at-3.21.46-PM.png" alt="" width="960" height="539"/>

◦ Lệnh cho phép các app không rõ nguồn gốc chạy được trên mac
sudo spctl —master-disable
◦ Lệnh cài đặt Xcode
xcode-select —install


...............................................:System:...............................................
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
- Card reader: Realtek PCI Express not work
- Monitor: 15.6" 16:9 HD (1366x768) LED Backlight
- Optical Drive: Super-Multi DVD (Optional).
    
...............................................:Status:...............................................
- Status Working:
  - Graphics (Intel HD4000)
  - Audio
  - WIFI
  - Bluetooth
  - Webcam
  - LAN
  - HDMI
  - VGA work but not good
  - Sleep, Processor Speedsteps and Native power management.
  - Trackpad
  - Fn Hotkeys
  - USB works
  - Disable turbo boost on battery (if neccessary)
  
- Status not working:
  + GT610M Graphics
  + Realtek CardReader
    
...............................................:Prepair:...............................................
- One USB 3.0 with 8Gb or higher
- Sources OS: http://osx.vn/threads/tong-hop-link-download-macos-10-4-10-12-2-orginal-tu-mac-app-store.286
- Sources code Terminal: 
  + 10.10: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Guide_Setup_OS_X_Yosemite.txt 
  + 10.11: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Guide_Setup_OS_X_El_Capital.txt 
  + 10.12: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Guide_Setup_macOS_Sierra.txt
  + (Please rename sources setup by copy sources setup to Application folder before run Terminal, rename UsbName to your usb name)
- Sources Clover: 
  + 10.10: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Clover_10.10_17-01-30.zip
  + 10.11: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Clover_10.11_17-01-30.zip
  + 10.12: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Clover_10.12_17-01-30.zip
- Sources Tool: 
  + Hackintosh Vietnam Tool V1.97 (if you install OS X 10.10 or 10.11, not working on 10.12)
  + Link download: https://drive.google.com/file/d/0B_rOF-XuryyyOTk5TjdqLUhRS28/view?usp=sharing
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
  +create part primary size=48500 (change 48,50Gb to your Gb you want to create, if you want create all please delete size=48500, with mac 48,50Gb = 50Gb)
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
- 10. Viethackintosh: https://viethackintosh.com/
- 11. Weloveapple: https://weloveapple.vn/

...........................................Thanks for visting and watching..........................................
<img class="alignnone size-full wp-image-487" src="https://viethackintosh.com/wp-content/uploads/2017/03/14470386_904489812989977_5266119457662626266_n.jpg" alt="" width="960" height="539" />

