# English

## Table of Contents
* [Feature Highlights](#feature-highlights)
  * Desktop Experience
  * Android Gaming
  * Others
* [Installation Targets](#installation-targets)
* [Installation Process Through Installer (UEFI 64-bit only)](#installation-process-through-installer-uefi-64-bit-only)
* [Manual Installation Process](#manual-installation-process)

## Feature Highlights
Desktop Experience
* Multi-window support with maximize, minimize, close, resize, etc.
* Option to disable multi-window for any app in case you need.
* General keyboard shortcuts like alt + tab, alt + f4, win + d etc.
* Close to AOSP experience with only necessary desktop features.
* Taskbar with the ability to pin apps, show notifications, and system icons.
  
Android Gaming
* Decapro key mapping tool to play games with keyboard and mouse (Press F12).
* Pre-mapped some popular games like PUBG, Subway Surfers, etc.
* GPU tools are available to fake GPU info for any game.
  
Others
* Open GApps included, no need to install them manually.
* OTA support is available, but only if you install it in an EXT4 RW partition.
* The feedback app is available for you guys to share your thoughts.
* Upstreamed kernel to Google LTS Linux 4.9. x.
  
## Installation Targets
* Hardware
  * Mac
  * PC
  * [Raspberry Pi](Raspberry%20Pi-en.md)
* QEMU
* [VirtualBox](VirtualBox-en.md)
* VMware

## Installation Process Through Installer (UEFI 64-bit only)
The PrimeOS installer has been released for installing PrimeOS on 64-bit UEFI systems in dual-boot mode alongside Windows.

Download the installer and follow the steps below for installing PrimeOS
* Launch the exe program and choose the drive from which you want to make a partition for PrimeOS.
* Input the space in MB for the new PrimeOS partition.
* Proceed to installation.
* Note: Ignore all the CMD and disk manager pop-ups for formatting the new partition.
* The system will restart, and the installation process will begin.
* After installation, you will have the boot menu for both PrimeOS and Windows.

## Manual Installation Process
USB Stick/Flash Drive Guide:
1. For this method, you need Etcher/[Rufus](Rufus-en.md), the PrimeOS iso file. We recommend using a decent-speed USB drive (8GB or larger).
2. For flashing PrimeOS to the USB drive, plug in your USB drive and launch Etcher/[Rufus](Rufus-en.md). Now select the PrimeOS iso file, and create the bootable USB.
3. Note: Be careful with the steps below and back up your data if you're not sure about what you are doing.
4. For installing PrimeOS on your HDD/SSD/SDcard, first create a new partition for PrimeOS ( suggested minimum size is 16GB ).
4. Turn off secure boot of your device and then boot up the PrimeOS USB by pressing Esc or F12, depending on your BIOS menu key, and selecting the PrimeOS USB to boot from.
6. Select the 'Install PrimeOS' option from the GRUB menu.
7. The installer will load, and you will have an option to choose which partition you created earlier. Choose it and select Ext4 to format the drive.
8. When it asks if you want to install the System as R/W (Read/Write), select YES. The OTA functionality will break.
9. When it asks if you want to install Grub, select YES.
10. When finished, the installer will then ask if you want to run PrimeOS. You can just reboot here and make sure you remove the USB drive.
