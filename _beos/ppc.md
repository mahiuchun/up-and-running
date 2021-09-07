---
name: BeOS ppc
title: BeOS on PowerPC
layout: default
---
# BeBox
Learn about it [here](https://en.wikipedia.org/wiki/BeBox)

I have never seen one in real life.
Suffice to say that it runs BeOS PPC (up to 5.0.3).

# Power Macintosh
Only a small number of Power Macintosh machines and clones are supported.
The rule of thumb is the following:
- The machine is shipped with PowerPC 600 series processor(s); excluding 601.
- The machine uses PCI (rather than NuBus).

See the original list by Be [here](http://testou.free.fr/www.beatjapan.org/mirror/www.be.com/support/guides/beosreadylist_ppc.html)

The BeOS editions CD-ROM are *NOT* bootable on Power Macintosh.
Instead, here are the steps to get it running:
1. Install some version of Mac OS 8 (Mac OS 9 does not work).
2. Insert BeOS CD-ROM and launch the installer in Mac OS. Perform the installation.
3. Reboot back to Mac OS and install OS picker extension in Mac OS.
4. An OS picker will show up starting from next boot.

# Tested Hardware

I've tested that the following hardware is working for BeOS ppc:
- Macintosh Performa 6400/200
- Twin Turbo 128M8 video card
- DEC 21041 network card (static IP only)
- Kingwin ADP-06 SATA to IDE bridge board and 120G SATA drive

# Software availability
The majority of BeOS applications are built for x86.
There is no emulation mechanism in BeOS for running x86 application on PowerPC or vice versa.

Look for "ppc" in filenames to identify applications built for PowerPC.

# Data Exchange
Haiku does not seem to support Apple partition map.
So data exchange through disks might be difficult.