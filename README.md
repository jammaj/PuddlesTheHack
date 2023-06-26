Asus Tuf Z390 Pro with AMD 570 Opencore EFI setup for hackintosh
=============

 Manifest lists all the files and where to get them.

 USBMap.kext 
 - 15 ports enabled, that is the limit for mac.  
 - 5 USB2 on back panel, USB2 disabled on port closest to the ethernet port ( U31G2_1 ). USB3* still works from that port.
 - 6 USB3* on back panel
 - 4 USB2+3 from USB3 front panel header U31G1_910 ( the one furthest from the CPU )

 Catalina 10.15.7

 i9900k

 - no Bluetooth card
 - no Wireless card

 iGPU needs to be connected to monitor at boot or it will not appear in system.
