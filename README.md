# Getting gdevilspie Running in Arch Linux

This fork fixes the issues with python2 so it will run on Arch and more modern linux/python.

In order to use on Arch you will need to make sure you have the following installed:

- pygtk
- python2-xdg
- intltool
- libwnck
- libgnome-keyring
- gnome-python (aur)
- python2-wnck (aur)

Unfortunately some of this is rather old and unmaintained so you will have to install some old stuff from aur.

1. Build gnome-python from aur
2. Build gnome-python-desktop from aur (this is the directory when cloning python2-wnck)

You should be able to run ./gdevilspie now.


# Original Readme

## gDevilspie svn

A user friendly interface to the devilspie window matching daemon, to create rules easily.

## Install

you can just run gdevilspie from the tarball if you don't want to install.

```
# ./gdevilspie
```

or install with setup.py:

```
$ python setup.py install
```

## AUTHORS

Mike Ryan: Patch for pyhton2 and archlinux
Islam Amer (phaeron)<iamer@open-craft.com>: Maintainer and lead developer
Kareem Kenawy <thesamo@gmail.com>: WNCK code and reader.

Thanks to CVirus for the systray code.
Enlightenment for the icon (window_new.png) under GPL.
python distrubution IRIX tools for the s-expression parser.
foosel for the rules wiki
Ross Burton for writing devilspie :)
