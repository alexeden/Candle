Up and Running on Mac
------------------

First get QT5:
`$  brew install qt5`

Link the binaries:
`$  brew link qt5 --force`

It might ask you to copy something into your bash profile. Do that.

Clone the repo, navigate to it, then build and run:
`$  qmake && make && ./src/candle/Candle.app/Contents/MacOS/Candle`

Config & First Carve
------------------

Included bit: 20˚ V bit, 1/8" shank

Measured z-probe height: 14.07mm

Probe command: `G21G91G38.2Z-45F100; G0Z1; G38.2Z-2F10; G92Z13.95; G0Z2`

After probing, enter: `G90 G0 Z0 F50`. This sets the router into absolute coordinate mode and goes to position 0 on the Z axis.
