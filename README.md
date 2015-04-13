# HiKey USB speed switching tool.

To install:
sudo cp ./usb_speed /usr/bin/usb_speed
sudo chmod a+x /usr/bin/usb_speed
sudo ln -s /usr/bin/usb_speed /usr/bin/get_usb_speed

To use:
$ usb_speed --help
usb_speed [-h | --help]			Displays this help text.
usb_speed [-q | --query]		Displays the current USB bus speed.
usb_speed [-s full | high]		Sets the USB bus speed to full or high speed.
usb_speed --full					Sets the USB bus speed to full speed.
usb_speed --high					Sets the USB bus speed to high speed.

$ get_usb_speed --help
get_usb_speed						Displays the current USB bus speed.
get_usb_speed [-h | --help]	Displays this help text.
