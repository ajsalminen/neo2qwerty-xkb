Neo2qwerty
==========

Introduction
------------

This is a modified version of the [Neo2 keyboard layout](http://www.neo-layout.org)
for X.
It replaces the custom layout of alphabet with the Finnish/Swedish QWERTY layout.
This is useful if you want to take advantage of the programming and other layers
without switching from plain old QWERTY. It should work on anything with XKB,
I currently use it on Ubuntu 12.04.

Usage
-----

Put the files somewhere like ~/.xkb. Add the following to your .xsession or
equivalent. On Ubuntu this [may require some additional tinkering](http://askubuntu.com/questions/254722/xsession-ignored-ubuntu-12-10).

        xkbcomp -I$HOME/.xkb ~/.xkb/keymap/neo2qwerty $DISPLAY

Install Neo2 according to [their instructions](http://wiki.neo-layout.org/wiki/Neo%20unter%20Linux%20einrichten/Aktivieren). On a fairly recent Ubuntu this
should be as simple as:
       dpkg-reconfigure keyboard-configuration

The modifications should now be done on login.