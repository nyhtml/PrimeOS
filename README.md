# PrimeOS
A complete desktop experience with access to millions of Android apps. It is designed to bring you the best of both worlds - a complete fusion of Android and PC.

## Feature Highlights
Desktop Experience
* Multi-window support with maximize, minimize, close, resize etc.
* Option to disable multi-window for any app in case you need.
* General keyboard shortcuts like alt + tab, alt + f4, win + d etc.
* Close to AOSP experience with only necessary desktop features.
* Taskbar with ability to pin apps, show notification and system icons.
  
Android Gaming
* Decapro key mapping tool to play games with keyboard and mouse (Press F12).
* Pre mapped some popular games like PUBG, Subway surf etc.
* GPU tools are available to fake gpu info for any game.
  
Others
* Open gapps included, no need to install them manually.
* OTA support is available but only if you install in EXT4 RW partition.
* Feedback app is available for you guys to share your thoughts.
* Up-streamed kernel to google LTS linux 4.9.x.
  
## Installation Process Through Installer (UEFI 64-bit only)
PrimeOS installer has been launched for installing PrimeOS in 64 bit UEFI systems in dual-boot mode alongside Windows.

Download the installer and follow the steps below for installing PrimeOS
* Launch the exe program and choose the drive from which you want to make a partition for PrimeOS.
* Input the space in MB for the new PrimeOS partition.
* Proceed to installation.
* Note : Ignore all the cmd and disk manager pop ups for formatting the new partition.
* The system will restart and installation process will begin.
* After installation, you will have the boot menu for both PrimeOS and Windows.

## Manual Installation Process
USB stick / Flash Drive guide:
1. For this method, you need Etcher / Rufus, PrimeOS iso file. We recommend you to use a decent speed USB drive (8GB or larger).
2. For flashing PrimeOS to the USB drive, plug in your USB drive and launch Etcher / Rufus. Now select PrimeOS iso file, create the bootable USB.
3. Note: Be careful with the steps below and backup your data if you're not sure about what you are doing.
4. For installing PrimeOS on your HDD/SSD/SDcard, first create a new partition for PrimeOS ( suggested minimum size is 16GB ).
4. Turn off secure boot of your device and then boot up the PrimeOS USB by pressing esc or F12, depending on your bios menu key and selecting the PrimeOS USB to boot from.
6. Select the â€˜Install PrimeOS option from GRUB menu.
7. The installer will load, and you will have an option to choose which partition you created earlier. Choose it, and select Ext4 for formatting the drive.
8. When it asks if you want to install System as R/W (Read/Write), select YES, otherwise the OTA functionality will break.
9. When it asks if you want to install Grub, select YES.
10. When finished, the installer will then ask if you want to run PrimeOS, you can just reboot here, and make sure you remove the USB drive.
