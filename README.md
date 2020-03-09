# specrend.js

A lightly modified JavaScript implementation of [the same program](https://www.fourmilab.ch/documents/specrend/) by John Walker originally written in C in 1996.

This version was written with the sole focus of converting a blackbody temperature to an RGB value.

The returned value from ```temperature_to_rgb``` is an object containing the r,g,b values as well as a boolean flag indicating whether the value was approximated from a colour outside the gamut.

Both the original [original C code](https://www.fourmilab.ch/documents/specrend/specrend.c) and the lightly modified implementation by Jacob Aulenback in JavaScript are in the Public Domain.
