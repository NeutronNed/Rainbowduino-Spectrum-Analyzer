Rainbowduino-Spectrum-Analyzer
==============================

Arduino files for the Rainbowduino based spectrum analyzer
I first got the Seeed Studio 3D LED Cube, which included a Rainbowduino as it's controller.  It looked like a lot of fun so I got the 8x8 RGB matrix and played with a bunch of the standard sketches. As a challenge, I thought I would create an 8x8 spectrum analyzer and Googled Arduino FFTs.  There wasn't a ton of resources, but it wasn't too bad.

SOFTWARE
You'll need the following libraries:
Rainbowduino library
FFFT library

and the following code:
rb_spectrum_analyzer.ino
ffft.h

HARDWARE
A Rainbowduino with an 8x8 RGB LED display and a simple audio input.
