dmenu - dynamic menu
====================
Personal fork of suckless.org's dmenu - an efficient dynamic menu for X.


Patches
------------
* fuzzymatch
* fuzzyhighlight
* password


Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Configuration
-------------
The configuration of dmenu is done by editing config.h and
(re)compiling the source code.


Running dmenu
-------------
See the man page for details.
