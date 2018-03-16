
Debian
====================
This directory contains files used to package citrusd/citrus-qt
for Debian-based Linux systems. If you compile citrusd/citrus-qt yourself, there are some useful files here.

## citrus: URI support ##


citrus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install citrus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your citrus-qt binary to `/usr/bin`
and the `../../share/pixmaps/citrus128.png` to `/usr/share/pixmaps`

citrus-qt.protocol (KDE)

