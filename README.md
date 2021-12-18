# s20-Series-GSI-Installation
Guide to install GSI ROM on Samsung Galaxy S20 Series 


I did search a lot no direct guide was available hence i am posting my steps to do the same. Let me know of any mistakes.

I tested this with DUJ5 Firmware. So i prefer you flash it if in beta or anything below that.

1)BootLoader Unlock

2)Flash TWRP - any TWRP will do not the lineage/dotos/pixelexperiece recovery. The unoffocial TWRP for s20 will be enough. Ill attatch the one I have with me here. Thanks to twrp-z3s-3.5.2_ianmacd+vbmeta-patched_DUH2. even though its DUH2 itll work.
https://www.mediafire.com/file/ud6iytybi0gc2w8/SUPER_GSI_Installer.zip/file
https://t.me/samsung_twrp_root/85280


3)Extract the gsi .xz file and copy the image file to the external_sd.

4)As the s20 is using a super partition, direct flash did not work for me. We will need to use the Super GSI installer. Download the attatched super gsi installer and move it to the same location as the gsi image.

5)The script looks its cwd for system.img file to flash, so rename the copied -arm64-ab.img to system.img.

6)Once everything is ready, reboot to the recovery, factory format data, clear everything as required, then flash this Super-GSI-Installer.zip file from the twrp.

7)Voila.. you can reboot once it shows the process completed to your new rom.

Notes;
I havent faced any performance issue in a daily driver use. However, the phone tends to heat up a bit when gaming and charging, compared to the custom lineage or similar tweaked roms for s20.

For camera you can use GCAM by BSG which i have tested and works as it does in the stock rom.

For the usb-c headphone, you can enable the tweaks from setting by phhusson

Let me know how it goes.

For GSI updates follow : https://t.me/treblegsis

Thanks to @phhusson for the GSI project and @ianmacd for the twrp. @ponces for earlybird pixelexperience implementation

If you use the phhusons aosp rom, you may face some issue with the twrp after the installation, when i tried to enter the recovery after the installation adn testing, i faced the recovery literally flashing on my display. with pixel experience i did not face that issue, maybe its my error.

link:https://forum.xda-developers.com/f/treble-enabled-device-development-a-ab-roms.7260/


Bugs with GSI A11/12
1)I personally is having trouble finding the auto brightness feature, the devs have enabled it in the rom but i havent cracked that one.
2)Proximity Sensor during call/ Accidental touch / Pocket detection seems to be missing.
3)Volte/Vowifi
4)and some other bugs but nothing i care except for these in day to day usage.
P.S. If anyone can suggest me any fixes for these it would be great.

PM me if any clarifications needed
>https://t.me/mr_scalpel
