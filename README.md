# PiScan

## About

This is a personal shopping and inventory-tracking device based on the [Raspberry Pi](http://www.raspberrypi.org/) and off-the-shelf [usb](https://en.wikipedia.org/wiki/USB) barcode scanners.

## Installation

## Usage


### Acknowledgements

 - Github user [danslimmon](https://github.com/danslimmon) for his [oscar](https://github.com/danslimmon/oscar) project, which inspired this one
 - [Vojtech Pavlik](http://atrey.karlin.mff.cuni.cz/~vojtech) for creating the [Linux Input Driver](http://atrey.karlin.mff.cuni.cz/~vojtech/input/) project
 - [linuxquestions.org](http://www.linuxquestions.org) user <tt>bricedebrignaisplage</tt> for his [post explaining how to read input devices](http://www.linuxquestions.org/questions/programming-9/read-from-a-usb-barcode-scanner-that-simulates-a-keyboard-495358/#post2767643)
 - Github user [gvalkov](https://github.com/gvalkov) for [golang-evdev](https://github.com/gvalkov/golang-evdev) which proved invaluable in implementing the [input_event struct](https://www.kernel.org/doc/Documentation/input/input.txt) in Go