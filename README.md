# OS Setup from scratch : A Complete Clean Installation Guide 
Detailed guide to setup Operating System and essential packages for Data Scientist starting from UEFI-BIOS splash screen 

## Contents in the order of setup :

0. UEFI BIOS EZ and Advanced Modes Usage
1. Bootable USB Drive Preparation
2. Ubuntu 2204
3. Wired Ethernet Driver
4. Nvidia Graphics Driver
5. Dual Screen Display
6. Google Chrome
7. Anydesk 6.2
8. VSCode
9. Python 3 extension for VSCode 
10. Anaconda
11. Cuda Cudnn
12. ROS2 (refer github.com/AmishaSomaiya/ROS2-Humble-Setup-On-Ubuntu2204.git) 

## Notes :
1. In case you cannot enter the BIOS mode, press the [ESC] or [F2] or [del]  key on the keyboard at boot time. If nothing works, remove the CMOS battery, wait for 3 minutes, put the CMOS battery back and restart

2. The bootable usb flash drive should compulsorily be of fat32 format. In case using an ssd or hard drive, ensure the format type is this. In case the hard drive format is different, for eg: exFAT, it is advisable to purchase a new flash drive (cost ~ 5-10$ for <=128GB as of 9/16/23) rather than changing format of hard drive because changing the format will risk spoiling the hard drive. Also note that any data other than the executable on the drive will be erased from the bootable drive.

3. Sometimes, after installing a package or an application, if it is still not being recognized, check environment path in bash file. If it is already present, it means it is correctly installed. But if it is still not recognized, try restarting the system. If everything fails, consider uninstalling and installing the application/ package again. 

WILL NOT WORK IF :
1. usb drive is password protected
seagate toolkit -> main menu -> seagate security -> disable protection
this can be enabled again when needed
2. has any corrupt file/ folder
factory settings -> reset drive 
3. is of file system of any format other than FAT32 : eg: exFAT 


stay tuned..
