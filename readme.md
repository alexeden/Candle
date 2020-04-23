Up and Running on Mac
------------------

First get QT5:
`$  brew install qt5`

Link the binaries:
`$  brew link qt5 --force`

It might ask you to copy something into your bash profile. Do that.

Clone the repo, navigate to it, then:
`$  cmake src/`
`$  make`

The app will be install as `Candle.app` at the project root.

Candle
-----------
GRBL controller application with G-Code visualizer written in Qt.

Supported functions:
* Controlling GRBL-based cnc-machine via console commands, buttons on form, numpad.
* Monitoring cnc-machine state.
* Loading, editing, saving and sending of G-code files to cnc-machine.
* Visualizing G-code files.


Build requirements:
------------------
Qt 5.4.2 with MinGW/GCC compiler
