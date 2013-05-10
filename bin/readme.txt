USBCopyNESBlue v5.0.1
Released by Brad Smith, 5/10/2013

This is a fork of the USBCopyNES client originally released by
Brian Parker (RetroUSB). This was in turn based on CopyNESW by
Quietust, which was in turn based on CopyNES by Kevin Horton.

http://www.retrousb.com/product_info.php?products_id=36
http://www.qmtpro.com/~nes/copynes/
http://kevtris.org/Projects/copynes/index.html

This project is publicly maintained on Google Code. The latest version,
as well as source code is available at:

http://code.google.com/p/usbcopynesblue/


Known Bugs:

 - CopyNES BIOS 4 NSF player copies song number into X and Y registers,
   causing dual NTSC/PAL NSFs to play at incorrect speed.


Changes:

v5.0.1 - 5/10/2013
 - NSF player now works with common RAM carts.
 - RAM cart code refactoring to allow use with other program functions.
 - Created U5ROM oversized UxROM plugin.
 - Fixed misnamed MMC6 WRAM writer in MAPPERS.DAT
 - New, more accurate set of VRC7 patches.
 - Fixed VRC7 patch tuner stop button (now releases note).
 - Fixed VRC7 patch tuner bug with saving patches.
 - Added VRC7 patch tuner keyboard function Q/W/E for Custom/Builtin/Stop.
 
v5.0.0 - 7/24/2012
 - Fixed bug in PowerPak Lite mapper selection.
 - Fixed bug in serial device initialization, now works on Windows 7.
 - Replaced C++ code in C files with valid C code.
 - Various source cleanup.
 