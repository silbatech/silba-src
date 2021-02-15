
Debian
====================
This directory contains files used to package silbad/silba-qt
for Debian-based Linux systems. If you compile silbad/silba-qt yourself, there are some useful files here.

## silba: URI support ##


silba-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install silba-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your silba-qt binary to `/usr/bin`
and the `../../share/pixmaps/silba128.png` to `/usr/share/pixmaps`

silba-qt.protocol (KDE)

