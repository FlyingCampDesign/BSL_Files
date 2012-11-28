OVERVIEW
========

Section 4.1 of TI's [slau319c.pdf](http://www.ti.com/lit/pdf/SLAU319) ("MSP430 Programming Via the Bootstrap Loader") describes simple and low-cost hardware and software solutions to access the bootstrap loader functions of the MSP430 flash devices through the serial port (RS-232) of a PC.  The [Flying Camp Design BSL Programmer](http://www.flyingcampdesign.com/msp430-bsl-programmer.html) mimics this hardware by providing a VCP interface to the BSL control software. However, unlike the hardware described in Section 4.1, the programmer does not invert the RST and TEST signals, and swaps the RST and TEST pins (with respect to the VCP RTS and DTR pins).  Therefore, it does not work out of the box with the utilities provided by TI's [slau319c.zip](http://www.ti.com/lit/zip/slau319).

This repository is an attempt to patch [slau319c.zip](http://www.ti.com/lit/zip/slau319) so that it works out of the box with the [Flying Camp Design BSL Programmer](http://www.flyingcampdesign.com/msp430-bsl-programmer.html).

STATUS
======

Currently only BSLDEMO2.exe has been patched and tested with an MSP430F1611.