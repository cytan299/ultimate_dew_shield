# Arduino source code

This directory contains the arduino source code for the Arduino Pro
Micro. The code has been successfully compiled using ARDUINO 1.6.5. It
**cannot** be compiled with later versions of the ARDUINO IDE because
the Pro Micro library is unsupported (as of 01 Jan 2016)! Sparkfun
knows about this and will eventually release a library that is
compatible with later versions of the ARDUINO IDE. Please follow the
instructions
[here](https://learn.sparkfun.com/tutorials/pro-micro--fio-v3-hookup-guide)
for installing the Pro Micro libraries.

## Note

The code assumes that _Tinside_ has index 0 and _Toutside_ has
index 1. You can change these indices by changing the defines TIN and
TOUT in the _controller.ino_ file.

## Directories

* **controller** This contains the *controller.ino* file which is the entry point
for the controller program.
* **lib** This contains the libraries which are required for compiling
  *controller*. The README.md file contains more information about
  these libraries.

## Copyright

The software that is written by the author is copyright 2016 C.Y. Tan
and released under GPLv3.




