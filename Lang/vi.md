# ASUS-K55VD-HACKINTOSH install OS X 10.10 Yosemite, OS X 10.11 El Capital, macOS 10.12 Sierra, macOS High Sierra 10.13
Make Laptop ASUS K55VD like Mac Book Pro 2012 late run real macOS.

![Screenshot](https://viethackintosh.com/wp-content/uploads/2017/03/ASUS2.jpg)
<strong>
	Mọi người thông cảm do hiện tại cáp quang đang đứt và một số việc học hành còn dang dở, và một macOS 10.12 mới cập nhật nên mình sẽ cập nhật thường xuyên thêm
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
		Hướng dẫn để cài đặt macOS Sierra 10.12 trên Laptop ASUS K55VD.
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
◦ Disable turbo boost on battery
<br>
<br>
<strong>
	Các thành phần không hoạt động:
</strong>
<br>
◦ GT610M Graphics
<br>
◦ Realtek CardReader
<br>
<br>
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
◦ Kext Network active Wi-Fi 9485: <h4>Fix WiFi folder</h4>
<br>
◦ Fix Graphics active Night Shift: <h4>Fix screen folder</h4>
<br>
◦ Folder Tools &amp; Software: <a href="/Software">Click here move to folder</a>
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
<br>
<strong>
	Phân vùng ổ cứng hệ thống
</strong>
<br>https://www.youtube.com/watch?v=uPbyxqggrA8
<br>
◦ Tạo bộ cài đặt trên USB: https://www.youtube.com/watch?v=P_O1PTPiQok
<br>
◦ Cài đặt macOS trên HDD: https://www.youtube.com/watch?v=P930Yx31GrU
<br>
◦ Hoàn thiện máy sau cài đặt: https://www.youtube.com/watch?v=XasTaBiUNWk
<br>
<br>
<strong>
Khởi động lại và xem kết quả và test lại toàn bộ hệ thống xem đã hoàn chỉnh chưa?
</strong>
<br><br>
<img class="alignnone size-full wp-image-562" src="https://viethackintosh.com/wp-content/uploads/2017/03/Screen-Shot-2017-04-04-at-3.21.46-PM.png" alt="" width="960" height="539"/>
<br><br>
◦ Lệnh cho phép các app không rõ nguồn gốc chạy được trên mac
<br>
	sudo spctl —master-disable
<br>
◦ Lệnh cài đặt Xcode
<br>
	xcode-select —install
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

![Screenshot](/Images/img10131.png)
