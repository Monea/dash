
Debian
====================
This directory contains files used to package monead/monea-qt
for Debian-based Linux systems. If you compile monead/monea-qt yourself, there are some useful files here.

## monea: URI support ##


monea-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install monea-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your monea-qt binary to `/usr/bin`
and the `../../share/pixmaps/monea128.png` to `/usr/share/pixmaps`

monea-qt.protocol (KDE)

