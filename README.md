# glados-18.04-x86_64
Glados is a science project aiming to run a full Linux operating system in RAM able to save persistent datas to disk. Glados provides LXDE desktop environment using Ubuntu LTS 64bits repositories. 

Depending on user choice at boot sequence, the operating system can be set to full load in RAM, or not.
User can install any software package from Ubuntu LTS repositories using apt command or synaptic, and even build its own modules, which can be fully loaded in RAM too at will.

French, english, german, spanish, and italian languages are built-in and user can install any other languages and/or keyboard availables from simple and easy tools. Glados provides full Ubuntu Internationalization and localization.

Project documentation is available inside the desktop. Glados project ships with xombrero browser, BBS tools, and highly improved desktop apps. More software can easily be installed. Pre-compiled modules can be downloaded from Glados home project website to add or replace the previous ones.

We hope you will support our project in participating or donating to our project.
https://www.patreon.com/littlebigone

https://opencollective.com/littlebigone
Many thanks in advance !

Enjoy science and have fun !

Laurent CAS, Research Director.

download:
https://glados-18-04-x86-64.sourceforge.io

*** HOW TO INSTALL GLADOS ***

Download the latest glados release, usually named from the Ubuntu LTS name convention.

Unzip the package inside a hard drive or a usb pendrive (which can be formatted fat32, vfat, ext3 or ext4, and ext3 is best)

Go to /linux/boot directory inside your target hard drive or usb pendrive, using a file manager or a terminal command.

Windows users will have to run bootinst.bat
Linux users will have to run bootinst.sh

Reboot your computer.

*** HOW TO INSTALL GLADOS MODULES ***

From inside Glados running in RAM, download your favorite module from Glados home project website and place it into your target hard drive or usb pendrive /media/glados/xxxxx/linux/modules directory using a file manager or a terminal command. Then reboot.

From inside Glados running normal, download your favorite module from Glados home project website and place it into your target hard drive or usb pendrive /run/initramfs/memory/toram directory using a file manager or a terminal command. Then reboot.

From another operating system, download your favorite module from Glados home project website and place it into your target hard drive or usb pendrive /linux/modules directory using a file manager or a terminal command. Then reboot.

*** *** ***
