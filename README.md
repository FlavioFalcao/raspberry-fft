
Raspberry-pi FFT
================

The current implementation of this project will read 
a sound stream from pipeline and apply the fft transform
to detect the main frequency of the input sound.

The idea is to use sound commands to control a vehicle
connected to the raspberry-pi.

Piece of cake instructions : 
-------------

To build : make
To run   : make run

Can it be easier than this?

To run other tests, please try : 
> cat samples/sample2.wav | ./exec

