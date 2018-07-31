
Debian
====================
This directory contains files used to package nobled/noble-qt
for Debian-based Linux systems. If you compile nobled/noble-qt yourself, there are some useful files here.

## noble: URI support ##


noble-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install noble-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your noble-qt binary to `/usr/bin`
and the `../../share/pixmaps/noble128.png` to `/usr/share/pixmaps`

noble-qt.protocol (KDE)

