# Arduino PSX Library

I'm putting this library on github so that it's accessible as a git submodule for my arduino
projects.

I originally found this library [here](http://playground.arduino.cc/Main/PSXLibrary)
on the Arduino Playground.  More documentation on the PSX controller
hardware can be found [here](http://www.gamesx.com/controldata/psxcont/psxcont.htm).

Add as a submodule to an arduino-make project with the following.  The
folder name must match the header file name (libraries/Psx ~ Psx.h).
You must then set up cmake to search for the library.

```
git submodule add git@github.com:dcunited001/arduino-psx.git libraries/Psx
```
