# Kindle specific mods to the imx_usb tool
This adds the kindle .conf and all required bins by default

Building on ubuntu requires libusb-1.0-0-dev. Just "make" it!

After building, run "./imx_usb path/to/bin/file.bin". Alternatively, you can use the tool "kindleselectboot" to launch a gui version of the tool. This automatically compiles the tool. Requires zenity.
