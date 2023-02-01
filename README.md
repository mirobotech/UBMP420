# UBMP420

UBMP420 (USB-Based Beginner Multipurpose Project 4, rev. 2) KiCad schematic and PCB design files.

<img width="1648" alt="UBMP420 KiCad" src="https://user-images.githubusercontent.com/4099144/216118879-23784358-fcbc-4477-9d04-41c842189321.png">

UBMP420 is a simple, versatile, and inexpensive microcontroller development system for everyone! The UBMP420 circuit board has a variety of simple I/O devices built-in so beginners can learn to code and make an assortment of different projects using just the parts on UBMP420 – no breadboarding, shields, or other modules are required, and external devices can be added on the expansion header. 

UBMP420 was designed for learning or teaching PIC programming in C or assembly language using either Microchip’s MPLAB X IDE or their MPLAB Xpress Cloud-based IDE. The [USB µC bootloader](https://hackaday.io/project/63204-usb-c-usb-pic-bootloader) allows UBMP420 to appear as a mass storage drive for easy programming. Simply drag and drop a compiled .hex file onto the ***PIC16F1459*** drive that shows up in your computer's device manager, and your program will start to run as soon as the file is transferred.

The bootloader makes it possible to program UBMP420 using almost any kind of device, even enabling schools with 1:1 Chromebook programs to teach real C language microcontroller programming with Github integration.

## UBMP420 Hardware Features

- Microchip PIC16F1459 USB-capable microcontroller with 8k words of program FLASH (6k words free when using the USB µC bootloader), 128B of user FLASH, 1kB of RAM, 10-bit ADC, and a built-in temperature sensor
- 5 built-in pushbuttons
- 5 visible light LEDs
- 1 piezo beeper output
- optional 8-pin header for PORTC I/O pin expansion (great for servos, a SONAR module, NeoPixels, an LCD display, etc.)
- optional IR LED output for remote control transmitter applications (or a high-current transistor-driven output)
- optional IR demodulator for remote control decoding
- optional IR phototransistor or visible-light ambient light sensor for light sensing
- USB 2.0 type-C port for power and programming
- 6-pin ICSP (In-Circuit Serial Programming) header for PICkit-4

![UBMP420](https://user-images.githubusercontent.com/4099144/216118986-c6f6ceb4-044e-4c06-9a5c-7d6922fab904.jpg)

## UMBP420 is Open

UBMP420 is open hardware and uses open source software – we want educators to have full access to the circuit, lesson materials, and code. The following permissions and conditions apply to UBMP420:
- the KiCad UBMP420 files stored in GitHub are open hardware licensed under the terms of the MIT license (except the mirobo.tech logo - see below). You are free to use and modify the UBMP420 files to make your own UBMP420 circuit boards.
- UBMP420 programs stored in GitHub are open source software licensed under the terms of the MIT license.
- UMBP420 learning materials on the mirobo.tech website are licensed under the terms of the Creative Commons CC-BY 4.0 license.
- the USB uC bootloader is open source and licensed under the terms of the GPL3.0 license by John Izzard.
- the mirobo.tech logo mark is a trademark of mirobo Technolgy and may not be used without prior permission.

## Can I buy a UBMP420?

UBMP420 boards, kits, and lab packs are available at [mirobo.tech](https://mirobo.tech/ubmp4).  
Bare UBMP420 printed circuit boards are also available from [OSHPARK](https://oshpark.com/shared_projects/LOHX7z0D).
