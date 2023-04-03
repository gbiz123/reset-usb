# reset-usb
##This program resets all USB ports on a Linux operating system.
This is useful when you get an annoying dmesg error 110, possible from USB power overdraw.
Run this script to avoid rebooting your computer.

##Installation:
```
git clone https://github.com/gbiz123/reset-usb
cp reset-usb/reset-usb ~/.local/bin
chmod +x ~/.local/bin/reset-usb
```

##Usage:
`sudo reset-usb`

All credit goes to hoijui on unix.stachexchange.com:
https://unix.stackexchange.com/questions/704341/how-to-reset-usb-controllers
