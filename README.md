STM32 with libopencm3
=====================

A project for the UKHAS 2014 conference to be used as a template for building
an STM32 project with libopencm3.  

# Requirements
This has only been tested with the gcc-arm-embedded toolchain. Grab the tarball
from the project page and put somewhere useful, then add the `/bin` folder to
your path. Test by running `arm-none-eabi-gcc --version`.  

You will also need Python and make installed.  

# Instructions

* Clone this repo somewhere
* Run `git submodule update --init`
* `cd` to the `firmware/libopencm3/` and run `make`.

## Author

Hacked together in half an hour and released into the public domain by Jon
Sowman, August 2014.  
