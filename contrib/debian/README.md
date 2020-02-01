
Debian
====================
This directory contains files used to package blessingd/blessing-qt
for Debian-based Linux systems. If you compile blessingd/blessing-qt yourself, there are some useful files here.

## blessing: URI support ##


blessing-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install blessing-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your blessing-qt binary to `/usr/bin`
and the `../../share/pixmaps/blessing128.png` to `/usr/share/pixmaps`

blessing-qt.protocol (KDE)

