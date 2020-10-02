
Debian
====================
This directory contains files used to package uiddd/uidd-qt
for Debian-based Linux systems. If you compile uiddd/uidd-qt yourself, there are some useful files here.

## uidd: URI support ##


uidd-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install uidd-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your uiddqt binary to `/usr/bin`
and the `../../share/pixmaps/uidd128.png` to `/usr/share/pixmaps`

uidd-qt.protocol (KDE)

