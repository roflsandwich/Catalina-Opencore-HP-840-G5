# Catalina-Opencore-HP-840-G5

Tested with BIOS 01.14.01

Forked From https://github.com/kecinzer/hpelitebook850g5-opencore

Everything working including Wi-fi, just need to disable trackpad forcetouch for optimal trackpad functioning.

How to Use

Installation:
1 - Follow this guide to create an OSX Install USB in Windows: https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html

2 - Copy EFI and com.apple.recovery.boot into Flashdrive root folder

3 - You need to change property ScanPolicy to 0 along with ShowPicker to true in EFI/OC/config.plist otherwise you don't see BaseSystem option in OpenCore boot menu!

4 - Run from flashdrive and install OSX


To use Opencore and this EFI to start OSX (You need to have OSX installed already):

If you installed using the previous instructions, restore the ScanPolicy and ShowPicker values in config.plist before copying the EFI folder.

1 - Mount the OSX EFI Folder in your hackintosh and replace the contents with this EFI folder.
