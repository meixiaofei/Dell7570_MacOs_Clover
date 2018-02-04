# macOS on DELL 7570
This project targets at giving the relatively complete functional ```macOS(what I use is 13.3)``` for Dell 7570, and all were have been driven except 940m and wifi.

# Environment
* Model：Dell Inspiron 7570
* CPU: i7-8550U(first I think it's coffee lake, but it seems just kaby lake)
* Video Card：Intel UHD Graphics 620(Ok) + NVIDIA GeForce 940m（Fail）
* Ethernet：Realtek RTL8168/8111/8112
* BlueTooth：Qualcomm 4.1
* Audio：Realtek ALC3254 

---
# Usage
Thanks to ```Rehabman```, his ```hotpatch``` let install black Mac so easy, you no more need to hack DSDT、SSDT, for more you can see [hotpatch](https://www.tonymacx86.com/threads/guide-using-clover-to-hotpatch-acpi.200137/).
- First, You should hava a bootable usb driver with ```CLOVER```(Baidu or Google how to).
- Then, put the whole ```CLOVER``` dir into the corresponding place in the above usb.
- Final, Reboot the computer, everything will be ok, Congratulation, have fun~

---
# Thanks
* [DalianSky](https://blog.daliansky.net/MacOS-installation-tutorial-XiaoMi-Pro-installation-process-records.html)
* [RehabMan](https://www.tonymacx86.com/members/rehabman.429483/)