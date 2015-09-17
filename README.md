isightcapture - capture image from quicktime video device

isightcapture [-v] [-d] [-n frame-no] [-w width] [-h height] [-t jpg|png|tiff|bmp] output-filename

Notes

This small CLI tool will be useful for grabbing images to implement simple webcams etc.

It will work without being logged and without a GUI window, unlike many other applications.

It only has been tested with MacOS X Tiger and iSight, but might well work with other setups.

Options

-v 		output version information and exit

-d		enable debugging messages. Off by default

-n		capture nth-frame

-w		output file pixel width. Defaults to 640 pixels.

-h		output file pixel height. Defaults to 480 pixels.

-t		output format - one of jpg, png, tiff or bmp. Defaults to JPEG.

Examples

$ ./isightcapture image.jpg

	will output a 640x480 image in JPEG format

$ ./isightcapture -w 320 -h 240 -t png image.png

	will output a scaled 320x240 image in PNG format

License

This utility is freeware. For questions regarding isightcapture, write to axel@intergalactic.de
