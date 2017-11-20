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
	- Realtek CardReader

## Yêu cầu: 
	- BIOS cài về mặc định: khởi động máy tính F2 &gt; F9 &gt; F10 &gt; Enter.
	- Một USB 3.0 8Gb hoặc cao hơn.
	- Sources OS link download: <a href="https://www.fshare.vn/file/AH8IJYXJJVGD" target="_blank">Fshare</a>
	- Một folder Clover EFI (DSDT, SSDT và tất cả các kext gơm lượm): <a href="https://github.com/southern21/ASUS-K55VD-HACKINTOSH" target="_blank">GitHub</a>
	- Kext Network active Wi-Fi 9485: <h4>Fix WiFi folder</h4>
	- Fix Graphics active Night Shift: <h4>Fix screen folder</h4>
	- Folder Tools &amp; Software: <a href="/Software">Click here move to folder</a>
	- Kext Utility V2.6.6 <a href="https://cvad-mac.narod.ru/files/Kext_Utility.app.v2.6.6.zip" target="_blank">Cvad-mac.narod.ru/</a>
	- Link Download MiniTool Partition Wizard Free Edition 10.2: <a href="https://download3.minitool.com/pw10/pw10-free.exe" target="_blank">Partitionwizard.com</a>
	- Folder Chứa các lệnh Terminal Prompt: <a href="https://github.com/southern21/ASUS-K55VD-HACKINTOSH" target="_blank">GitHub</a>
	- 30 – 40 phút cài đặt.
	- Mình cài trên HDD chuẩn EFI nhé
	- Một Laptop chạy Windows 7 hoặc cao hơn

## Cài đặt

### Phân vùng ổ cứng hệ thống

  **&nbsp;**

     https://www.youtube.com/watch?v=uPbyxqggrA8

### Tạo bộ cài đặt trên USB:  

  **&nbsp;**

     https://youtu.be/9GjaZQTLVeQ

### Cài đặt macOS trên HDD:

  **&nbsp;**

     https://www.youtube.com/watch?v=7gG6liug2w8

### Hoàn thiện máy sau cài đặt: 

  **&nbsp;**

     

### Khởi động lại và xem kết quả và test lại toàn bộ hệ thống xem đã hoàn chỉnh chưa?
**Lệnh cho phép các app không rõ nguồn gốc chạy được trên mac**

	sudo spctl —master-disable

**Lệnh cài đặt Xcode**

	xcode-select —install



