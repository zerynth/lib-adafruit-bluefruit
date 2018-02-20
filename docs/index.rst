*********
Bluefruit
*********

Adafruit Bluefruit LE SPI products family enables Bluetooth Low Energy connectivity to anything that supports SPI communication. Thanks to the connection between the Bluefruit LE chip and the device using the common four-pin SPI interface (MISO, MOSI, SCK and CS/SSEL), it is possible to enable the solution with wireless communication features; more information at `Adafruit dedicated page <https://www.adafruit.com/products/2746>`_

=================
Technical Details
=================

* ARM Cortex M0 core running at 16MHz
* 256KB flash memory
* 32KB SRAM
* Transport: SPI at 4MHz with HW IRQ
* 5V-safe inputs
* On-board 3.3V voltage regulation
* Bootloader with support for safe OTA firmware updates
* Easy AT command set to get up and running quickly

Here below, the Zerynth driver for the Adafruit Bluefruit LE SPI products family and some examples to better understand how to use it.

.. include:: __toc.rst
