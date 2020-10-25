# ulisp-arm
A version of the Lisp programming language for boards based on the ARM processor:

* Arduino Zero and MKRZero.
* Adafruit ItsyBitsy M0, Feather M0, and Gemma M0.
* Adafruit Metro M4, ItsyBitsy M4, Feather M4, and Grand Central M4.
* Adafruit PyBadge and PyGamer.
* Adafruit CLUE and ItsyBitsy nRF52840.
* BBC Micro Bit.
* Maxim MAX32620FTHR.
* Teensy 4.0/4.1.

For more information see: http://www.ulisp.com/


Added to my fork:
* Made version string a constant and put up top for easy mod
* Added list support for subseq
* Added is-available to check to see if a serial read will block
* Added gc-threshold to set your own GC threshold (for garbage collection). This gives you finer grain control (you can lower/disable garbage collection
during critical "soft-realtime" parts of your code)
