Ultimate Hacking Keyboard electronics
=====================================

[![Changelog #186](https://img.shields.io/badge/changelog-%23186-lightgrey.svg)](https://changelog.com/186)

Contained are the schematics and board layout KiCad files for the [Ultimate Hacking Keyboard](https://ultimatehackingkeyboard.com/).

Please make sure to clone this repo with:

`git clone --recursive git@github.com:UltimateHackingKeyboard/electronics.git`

Now, you should be able to open any of the 4 [KiCad](http://kicad-pcb.org/) projects of the repo:

* [left-main](left-main) contains main PCB of left keyboard half.
* [right-main](right-main) contains the main PCB of the right keyboard half.
* [display](display) contains the PCB that interfaces our custom manufactured LED segment display with the left main PCB.
* [connector](connector) is a very small PCB that is soldered vertically to the right main circuit board to act as the female board to board that interconnects the keyboard halves without needing a bridge cable.
