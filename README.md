A small board designed to replace the proprietary Nintendo 3DS dock charging port with a USB type C port. This board is suitable for official Nintendo 3DS, New 3DS, 3DS XL and New 3DS XL docks, which all contain the same small PCB on the inside.

Features:
* Includes pads for 5.1k&#937; resistors, to allow the use of 'smart' chargers.
* Board is a near drop-in replacement for the original.
* Pads on the + output allow the addition of a switch - bridge these pads with solder if you're not using one. Alternatively, use the switchless version of the board.

Minor alterations to the dock are required, due to the USB type C port being physically larger than the original. More details on the required sanding can be found [on my blog](https://qubitsandbytes.co.uk/convert-a-nintendo-3ds-dock-to-usb-c/).

Included in this repository are the KiCAD files for this design. If you're only interested in having the board manufactured, gerbers are available under 'releases'.

Parts List:
* 1x 16 pin USB type C port
* 2x 0603 5.1k&#937; resistors (optional)
* 1x 2 pin switch (optional)

A tri-wing screwdriver is required, to remove the dock base.

When having the board manufactured, ensure they offer a 0.8mm board thickness - I used OSH Park for mine.

## Images
KiCAD render:

![KiCAD render](render.png?raw=true "KiCAD render of the board")

## KiCAD
The files in this project were created using KiCAD 7. Older versions of KiCAD will be unable to open these files.

In addition, the USB Type C port pictured in the 3D render can be found [over here](https://github.com/ai03-2725/Type-C.pretty) - the file you're looking for is 'HRO TYPE-C-31-M-12.step'. It's not required, unless you want to see the part populated using the 3D viewer.
