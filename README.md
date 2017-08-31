# ASUS-K55VD-HACKINTOSH install OS X 10.10 Yosemite, OS X 10.11 El Capital, macOS 10.12 Sierra
Make Laptop ASUS K55VD like Mac Book Pro 2012 late run real macOS.

<img class="alignnone size-full wp-image-486 alignright" src="https://viethackintosh.com/wp-content/uploads/2017/03/ASUS2.jpg" alt="" width="960" height="539"/>
<strong>
	Mọi người thông cảm do hiện tại cáp quang đang đứt và một số việc học hành còn dang dở, và một macOS 10.12.4 mới cập nhật nên mình sẽ cập nhật thường xuyên thêm
</strong>
<h3 style="text-align: center">
	..............................................................................................
</h3>
<center>
	<h3 style="text-align: center">
		<strong>
			Vietnamese Ver: Updated soon
		</strong>
		<br>
		Hướng dẫn để cài đặt macOS Sierra 10.12.4 trên Laptop ASUS K55VD.
	</h3>
</center>
<br>
<strong>
	Cấu hình cơ bản:
</strong>
<br>
◦ Processor : Intel(R) Core(TM) i5-3210M CPU @ 2.50GHz (Ivy Bridge)
<br>
◦ Graphics Processor(GPU) : Intel HD4000 and Nvidia Optimus GT610M with 2GB DDR3 VRAM
<br>
◦ Hard disk : HDD Hitachi 500GB
<br>
◦ RAM : 6GB DDR3 / bus 1600
<br>
◦ Wifi + Buetooth: Qualcomm Atheros AR9485WB-EG
<br>
◦ LAN : Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter
<br>
◦ Audio : Realtek ALC270
<br>
◦ USB 3.0 : Intel 7 series/210 USB 3.0
<br>
◦ Touchpad : Elan Touchpad
<br>
◦ Webcam : 0.3 Web Camera
<br>
◦ Card reader : Realtek PCI Express
<br>
◦ Monitor: 15.6" 16:9 HD (1366x768) LED Backlight
<br>
◦ Optical Drive: Super-Multi DVD (Optional) 
<br>

<br>
<strong>
	Các thành phần hoạt động tốt:
</strong>
<br>
◦ Graphics (Intel HD4000)
<br>
◦ Audio
<br>
◦ WIFI + Bluetooth
<br>
◦ LAN
<br>
◦ Webcam
<br>
◦ HDMI
<br>
◦ VGA
<br>
◦ Sleep, Processor Speedsteps and Native power management.
<br>
◦ Trackpad cảm ứng đa điểm 4 ngón
<br>
◦ Fn Hotkeys
<br>
◦ USB works
<br>
◦ Realtek CardReader
<br>
◦ Disable turbo boost on battery

<br>
<br>
<strong>
	Các thành phần không hoạt động:
</strong>
<br>
<br>
◦ GT610M Graphics

<strong>
	Yêu cầu:
</strong>
<br>
◦ BIOS cài về mặc định: khởi động máy tính F2 &gt; F9 &gt; F10 &gt; Enter.
<br>
◦ Một USB 3.0 8Gb hoặc cao hơn.
<br>
◦ Sources OS link download: <a href="https://www.fshare.vn/file/AH8IJYXJJVGD" target="_blank">Fshare</a>
<br>
◦ Một folder Clover EFI (DSDT, SSDT và tất cả các kext gơm lượm): <a href="https://github.com/southern21/ASUS-K55VD-HACKINTOSH" target="_blank">GitHub</a>
<br>
◦ Kext Network active Wi-Fi 9485 &amp; Graphics active Night Shift: <a href="https://github.com/southern21/ASUS-K55VD-HACKINTOSH" target="_blank">GitHub</a>
<br>
◦ Folder Tools &amp; Software: <a href="https://drive.google.com/drive/folders/0B_rOF-XuryyyR2c0STJKV3dwanc?usp=sharing" target="_blank">Google Drive</a>
<br>
◦ Kext Utility V2.6.6 <a href="https://cvad-mac.narod.ru/files/Kext_Utility.app.v2.6.6.zip" target="_blank">Cvad-mac.narod.ru/</a>
<br>
◦ Link Download MiniTool Partition Wizard Free Edition 10.2: <a href="https://download3.minitool.com/pw10/pw10-free.exe" target="_blank">Partitionwizard.com</a>
<br>
◦ Folder Chứa các lệnh Terminal Prompt: <a href="https://github.com/southern21/ASUS-K55VD-HACKINTOSH" target="_blank">GitHub</a>
<br>
◦ 30 – 40 phút cài đặt.
<br>
◦ Mình cài trên HDD chuẩn EFI nhé
<br>
◦ Một Laptop chạy Windows 7 hoặc cao hơn
<br>

<strong>
	Phân vùng ổ cứng hệ thống
</strong>
<br>
[embed]
	https://www.youtube.com/watch?v=uPbyxqggrA8
[/embed]

<br>
◦ Tạo bộ cài đặt trên USB
[embed]
	https://www.youtube.com/watch?v=P_O1PTPiQok
[/embed]


<br>
◦ Cài đặt macOS trên HDD:
[embed]
	https://www.youtube.com/watch?v=P930Yx31GrU
[/embed]


<br>
◦ Hoàn thiện máy sau cài đặt:
[embed]
	https://www.youtube.com/watch?v=XasTaBiUNWk
[/embed]


<br>
Khởi động lại và xem kết quả và test lại toàn bộ hệ thống xem đã hoàn chỉnh chưa?

<img class="alignnone size-full wp-image-562" src="https://viethackintosh.com/wp-content/uploads/2017/03/Screen-Shot-2017-04-04-at-3.21.46-PM.png" alt="" width="960" height="539"/>

<br>
◦ Lệnh cho phép các app không rõ nguồn gốc chạy được trên mac
<br>
	sudo spctl —master-disable
<br>
◦ Lệnh cài đặt Xcode
<br>
	xcode-select —install
<br>


...............................................:System:...............................................
<br>
- Processor : Intel(R) Core(TM) i5-3210M CPU @ 2.50GHz (Ivy Bridge)
<br>
- Graphics Processor(GPU) : Intel HD4000 and Nvidia Optimus GT610M with 2GB DDR3 VRAM
<br>
- Hard disk : HDD Seagate 500GB
<br>
- RAM : 6GB DDR3 / bus 1600
<br>
- Wifi : Qualcomm Atheros AR9485WB-EG
<br>
- LAN : Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter
<br>
- Audio : Realtek ALC270
<br>
- USB 3.0 : Intel 7series/210 USB 3.0
<br>
- Touchpad : Elan Touchpad
<br>
- Webcam : 0.3 Web Camera
<br>
- Card reader: Realtek PCI Express
<br>
- Monitor: 15.6" 16:9 HD (1366x768) LED Backlight
<br>
- Optical Drive: Super-Multi DVD (Optional).
<br>
    
...............................................:Status:...............................................
<br>
- Status Working:
<br>
  - Graphics (Intel HD4000)
<br>
  - Audio
<br>
  - WIFI
<br>
  - Bluetooth
<br>
  - Webcam
<br>
  - LAN
<br>
  - HDMI
<br>
  - VGA work but not good
<br>
  - Sleep, Processor Speedsteps and Native power management.
<br>
  - Trackpad
<br>
  - Fn Hotkeys
<br>
  - USB works
<br>
  - Disable turbo boost on battery (if neccessary)
<br>
  + Realtek CardReader
<br>
  
- Status not working:
<br>
  + GT610M Graphics
<br>
    
...............................................:Prepair:...............................................
- One USB 3.0 with 8Gb or higher
<br>
- Sources OS: http://osx.vn/threads/tong-hop-link-download-macos-10-4-10-12-2-orginal-tu-mac-app-store.286
<br>
- Sources code Terminal: 
  + 10.10: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Guide_Setup_OS_X_Yosemite.txt 
<br>
  + 10.11: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Guide_Setup_OS_X_El_Capital.txt 
<br>
  + 10.12: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Guide_Setup_macOS_Sierra.txt
<br>
  + (Please rename sources setup by copy sources setup to Application folder before run Terminal, rename UsbName to your usb name)
<br>
- Sources Clover: 
<br>
  + 10.10: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Clover_10.10_17-01-30.zip
<br>
  + 10.11: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Clover_10.11_17-01-30.zip
<br>
  + 10.12: https://github.com/southern21/ASUS-K55VD-HACKINTOSH/blob/master/Clover_10.12_17-01-30.zip
<br>
- Sources Tool: 
<br>
  + Hackintosh Vietnam Tool V1.97 (if you install OS X 10.10 or 10.11, not working on 10.12)
<br>
  + Link download: https://drive.google.com/file/d/0B_rOF-XuryyyOTk5TjdqLUhRS28/view?usp=sharing
<br>
- 30 minutes to setup or higher
<br>
- A PC run mac OS or virtual machine run on Windows 7 or higher
<br>
    
...............................................:Install:...............................................
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
- Plug in usb to usb 3.0 port and Format usb with 2 partition: 1Gb for "ESP" with Fat and the rest Gb for UsbName with HFS+ (notes: Format with GUID Partition MAP)
<br>
- Download source setup and copy it to Application folder
<br>
- Download and open file sources code ".txt" for Terminal which OS you want to setup
<br>
- Open Terminal and copy and paste from first line to final line.
<br>
-  After it all, copy Clover folder go to Volume Fat of USB like "ESP" 
<br>
(if can't boot please remove folder APPLE) 
<br>
(Or you can copy folder to Volume EFI on HDD and create boot from BIOS)
<br>
- Done. Reboot and Press ESC to choose boot 
<br>
(please choose first line: "UEFI USB....").
<br>
-  After boot please choose Continue > Agree > Agree > choose your volume to install 
<br>
	(Look in menu bar and choose Utilities > Disk Utility > Choose your label volume "Macintosh HD" or your volume name and Earse with HFS+) 
<br>
	like "Macintosh HD" > Install > Done. Wait for a few minutes your laptop will reboot.
<br>
- After reboot: Choose your country > keyboard > Choose your network > Transfer do not > Enable Location > Login icloud (if you need or skip) > Agree with Term and Condition > Create your account and set time zone > Diagnostic & Usage > Done.
<br>
- Modify OS
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

