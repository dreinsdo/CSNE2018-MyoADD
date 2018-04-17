# Overview

The codebase was taken from:

**https://github.com/dzhu/myo-raw**

We have modified **myo.py** to read in data from analog force resistor that
would then get converted by ADS 1015 and send a vibration signal back to
Myo band by use of RaspberryPi 3.

It was also modified to read custom gestures from Myo band and send signals
via GPIO ports to control the motor to change grips.

# Installation

Important information can be found in the original README provided by github.com/dzhu