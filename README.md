This program resets all USB ports on a Linux operating system.
This is useful when you get an annoying dmesg error 110, possible from USB power overdraw.
Run this script to avoid rebooting your computer.

Installation:
Put the script in your ~/.local/bin directory
chmod +x reset-usb
sudo reset-usb

All credit goes to hoijui on unix.stachexchange.com:
https://unix.stackexchange.com/questions/704341/how-to-reset-usb-controllers
