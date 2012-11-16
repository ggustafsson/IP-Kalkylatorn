IP-Kalkylatorn (ipkalk)
=======================

![ipkalk](https://github.com/ggustafsson/IP-Kalkylatorn/raw/master/Preview.png)

Description
-----------
This script is a fork of ipcalc (0.41). It's basically the same program but
with a lot of small improvements to the output (and a huge amount of cleaning
under the hood).

The program takes an IP address and netmask and calculates the resulting
network address, wildcard mask, broadcast address and host range. By
specifying a second netmask you can design subnets and supernetworks.

Usage
-----
It's really easy to use ipkalk. Run the script for example usage.

    ./ipkalk --help

Dependencies
------------
You need to have **Perl** installed to run this.

Help out
--------
The basic functionality is all there but there is a lot of small issues with
the script so if you know Perl and want to help out please take a look at the
TODO file (or just check the source file for errors). If you don't mind
reinventing the wheel then a complete rewrite might be in order.

I don't plan on doing much more work with this script since i don't know Perl.

License
-------
Based on ipcalc (0.41) created by Krischan Jodies (krischan at jodies.de).
Forked and modified by Göran Gustafsson (gustafsson.g at gmail.com).

Released under the GNU General Public License, version 2 or later.

    Copyright (C) 2004  Krischan Jodies
    Copyright (C) 2012  Göran Gustafsson

    This program is free software; you can redistribute it and/or modify it
    under the terms of the GNU General Public License as published by the
    Free Software Foundation; either version 2 of the License, or (at your
    option) any later version.

    This program is distributed in the hope that it will be useful, but
    WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General
    Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    59 Temple Place, Suite 330, Boston, MA 02111-1307 USA

