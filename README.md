#dmenu - dynamic menu
dmenu is an efficient dynamic menu for X.


##Requirements
In order to build dmenu you need the Xlib header files.
On Ubuntu, this may require installing libxinerama-dev

##Installation
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install

##Patches
This build of dmenu has the following patches:
1. Border
2. Center
3. lineheight
4. xresources
5. xyw

###Xresources
Colors that can be set in Xresources file:
dmenu.font
dmenu.background
dmenu.foreground
dmenu.selbackground
dmenu.selforeground

##Running dmenu
See the man page for details.

