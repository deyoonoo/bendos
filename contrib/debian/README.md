
Debian
====================
This directory contains files used to package bdsd/bds-qt
for Debian-based Linux systems. If you compile bdsd/bds-qt yourself, there are some useful files here.

## bds: URI support ##


bds-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bds-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bds-qt binary to `/usr/bin`
and the `../../share/pixmaps/bds128.png` to `/usr/share/pixmaps`

bds-qt.protocol (KDE)

