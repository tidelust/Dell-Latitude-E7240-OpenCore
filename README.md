# Dell-Latitude-E7240-OpenCore
OpenCore boot pack for Dell Latitude E7240
<br>
Tested on macOS Catalina 10.15 with Core i7-4600U
<br>
<h2>How to install</h2>
1. Simply download or clone this repo.<br>
2. Mount your EFI partition (this can be your internal disk or portable drives).<br>
3. Create a directory named "EFI", if it already exists delete everything inside it.<br>
4. Copy/move "BOOT" and "OC" folders to the "EFI" folder.<br>
5. Done! Enjoy your Hackintosh.<br>
<br>
<h2>Some notes for a fully functional Hackintosh!</h2>
1. To fix iServices (iMessage and FaceTime), please generate your own serial number, MLB, MAC address, etc. with GenSMBIOS https://github.com/corpnewt/GenSMBIOS. <b>For this particular model I use MacbookPro11,4 SMBIOS</b><br>
2. This particular configuration requires you to modify the DVMT pre-allocated memory using GRUB shell (you can Google this to download by yourself) <b>or it will not boot at all due to low memory,</b> courtesy of OSXLatitude https://osxlatitude.com/forums/topic/6472-dell-latitude-e7240e7440/?do=findComment&comment=101125<br>
3. Note that you might need to update your kexts if available! See OpenCore Post-install docs https://dortania.github.io/OpenCore-Post-Install/universal/update.html
4. I no longer own this laptop, so if you had any issues regarding to patches or anything related please attach DSDT (select acpidump.efi in OC boot picker) and last logs.
<h2>Known issues</h2>
1. Brightness keys not working (both Fn + Up and Fn + Down), instead pressing Pause (Fn + Insert) to increase or Scroll lock (Fn + F3) to decrease will do the job.
2. You tell me.
