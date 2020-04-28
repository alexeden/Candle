Up and Running on Mac
------------------

First get QT5:
`$  brew install qt5`

Link the binaries:
`$  brew link qt5 --force`

It might ask you to copy something into your bash profile. Do that.

Clone the repo, navigate to it, then build and run:
`$  qmake && make && ./src/candle/Candle.app/Contents/MacOS/Candle`
