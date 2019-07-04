C++ I2C LCD Backpack library
============================

A simple, basic library for interfacing with an I2C LCD "backpack".

Dependencies
-----
For abstraction of communication with microcontrollers, this library uses [hwlib](http://github.com/wovo/hwlib) and it's bitbanged I2C implementation.

The included makefile is built for [BMPTK](http://github.com/wovo/bmptk) although this is not necessary.

Installation
-----
- Download the library `git clone http://github.com/Niels-Post/cpp_i2c_lcd`
- Include Makefile.inc from your project

Building with BMPTK
----



Building without BMPTK
----
The included makefile only sets some variables, but doesn't do any compiling itself. When building without BMPTK, some variables should be interpreted properly after including.
- HEADERS: all .hpp header files
- SOURCES: all .cpp source files
- SEARCH: theinclude path for header files of this library 


