# Kindle specific mods to the imx_usb tool
This adds the kindle .conf and all required bins by default

Building on ubuntu requires libusb-1.0-0-dev. Just "make" it!

After building, run "./imx_usb path/to/bin/file.bin". 
Alternatively, you can use the tool "imx\_gui" or "imx\_tui" to launch a gui/tui version of the tool respectivly. 
This automatically compiles the tool. Requires zenity/whiptail (zenity comes standard with desktop ubuntu, whiptail comes as part of debian base system ).
