# How to install OS X 10.10 Yosemite, OS X 10.11 El Capital, macOS 10.12 Sierra, macOS High Sierra 10.13 on Laptop ASUS K55VD

Make Laptop ASUS K55VD like Mac Book Pro 2012 late run real macOS.
This is a working set of kexts and configurations for running OS X, macOS for laptop ASUS K55VD.


# Hướng dẫn để cài đặt macOS High Sierra 10.13 trên Laptop ASUS K55VD.

## Cấu hình cơ bản:
  - Processor : Intel(R) Core(TM) i5-3210M CPU @ 2.50GHz (Ivy Bridge)
  - Graphics Processor(GPU) : Intel HD4000 and Nvidia Optimus GT610M with 2GB DDR3 VRAM
  - Hard disk : HDD Hitachi 500GB
  - RAM : 6GB DDR3 / bus 1600
  - Wifi + Buetooth: Qualcomm Atheros AR9485WB-EG
  - LAN : Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter
  - Audio : Realtek ALC270
  - USB 3.0 : Intel 7 series/210 USB 3.0
  - Touchpad : Elan Touchpad
  - Webcam : 0.3 Web Camera
  - Card reader : Realtek PCI Express
  - Monitor: 15.6" 16:9 HD (1366x768) LED Backlight
  - Optical Drive: Super-Multi DVD (Optional) 

## Các thành phần hoạt động tốt:
  - Graphics (Intel HD4000)
  - Audio
  - WIFI + Bluetooth
  - LAN
  - Webcam
  - HDMI
  - VGA
  - Sleep, Processor Speedsteps and Native power management.
  - Trackpad cảm ứng đa điểm 4 ngón
  - Fn Hotkeys
  - USB works
  - Disable turbo boost on battery

## Các thành phần không hoạt động:
  - GT610M Graphics
  - Realtek CardReader (thi thoảng hoạt động)

## Yêu cầu: 
  - BIOS cài về mặc định: khởi động máy tính F2 &gt; F9 &gt; F10 &gt; Enter.
  - Một USB 3.0 8Gb hoặc cao hơn.
  - Sources OS link download: 
  
  **&nbsp;**
  
       https://pastebin.com/fubebWzy

  - Một folder Clover EFI (DSDT, SSDT và tất cả các kext gơm lượm): 
  	- 10.10: <a href="/10.10.5">Click here move to folder.</a>
  	- 10.11: <a href="/10.11.6">Click here move to folder.</a>
  	- 10.12: <a href="/10.12.6">Click here move to folder.</a>
  	- 10.13: <a href="/10.13.6">Click here move to folder.</a>
  	- 10.14: <a href="/10.14">Click here move to folder.</a>


## DOWNLOAD: PLEASE CHECK MY RELEASES.

   https://github.com/southernvevo/ASUS-K55VD-HACKINTOSH/releases/

    
  - Folder Tools &amp; Software: <a href="/Software">Click here move to folder</a>
  - Kext Utility V2.6.6 <a href="https://cvad-mac.narod.ru/files/Kext_Utility.app.v2.6.6.zip" target="_blank">Click here to download</a>
  - Link Download MiniTool Partition Wizard Free Edition 10.2: <a href="https://download3.minitool.com/pw10/pw10-free.exe" target="_blank">Click here to download</a>
  - Folder Chứa các lệnh Terminal Prompt: 
	- 10.10: <a href="https://raw.githubusercontent.com/southernvevo/ASUS-K55VD-HACKINTOSH/master/Command%20Prompt/Guide%20Setup%20OS%20X%20Yosemite%2010.10.txt">Guide Setup OS X Yosemite 10.10</a>
	- 10.11: <a href="https://raw.githubusercontent.com/southernvevo/ASUS-K55VD-HACKINTOSH/master/Command%20Prompt/Guide%20Setup%20OS%20X%20El%20Capital%2010.11.txt">Guide Setup OS X El Capital 10.11</a>
	- 10.12: <a href="https://raw.githubusercontent.com/southernvevo/ASUS-K55VD-HACKINTOSH/master/Command%20Prompt/Guide%20Setup%20macOS%20Sierra%2010.12.txt">Guide Setup macOS Sierra 10.12</a>
	- 10.13: <a href="https://raw.githubusercontent.com/southernvevo/ASUS-K55VD-HACKINTOSH/master/Command%20Prompt/Guide%20Setup%20macOS%20High%20Sierra%2010.13.txt">Guide Setup macOS High Sierra 10.13</a>
	- 10.14: <a href="https://raw.githubusercontent.com/southernvevo/ASUS-K55VD-HACKINTOSH/master/Command%20Prompt/Guide%20Setup%20macOS%20Mojave%2010.14.txt">Guide Setup macOS Mojave 10.14</a>
  - 30 – 40 phút cài đặt.
  - Mình cài trên HDD chuẩn EFI nhé.
  - Một Laptop chạy Windows 7 hoặc cao hơn.

## Cài đặt

### Phân vùng ổ cứng hệ thống

  **&nbsp;**

     https://www.youtube.com/watch?v=uPbyxqggrA8

### Tạo bộ cài đặt trên USB:

  **&nbsp;**

     https://youtu.be/9GjaZQTLVeQ

### Cài đặt macOS trên HDD:
  **&nbsp;**

     https://youtu.be/7gG6liug2w8

### Hoàn thiện máy sau cài đặt: 
  - Kext Network active Wi-Fi athr9485.
  
  **&nbsp;**

     https://youtu.be/JU6qUJ-MpA0

  - Fix Graphics active Night Shift.
  
  **&nbsp;**

     https://youtu.be/8XlJ8UN94Ho
     
  - Cài đặt Clover EFI Bootloader cho phân vùng Macintosh HD.
  
  **&nbsp;**

     https://youtu.be/W5pLM5bKfaA

  - Tạo file SSDT hoạt động hiệu năng của CPU.  
  
  **&nbsp;** 

     https://youtu.be/wSqNAt8mHGE

  - Cài kext Audio sửa lỗi mất âm thanh sau khi gập Laptop.  
  
  **&nbsp;** 

     https://youtu.be/kXXDElK2EA8

## Khởi động lại và xem kết quả và test lại toàn bộ hệ thống xem đã hoàn chỉnh chưa?
**Lệnh cho phép các app không rõ nguồn gốc chạy được trên mac**

	sudo spctl —master-disable

**Lệnh cài đặt Xcode**

	xcode-select —install



