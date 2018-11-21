
Debian
====================
This directory contains files used to package banderad/bandera-qt
for Debian-based Linux systems. If you compile banderad/bandera-qt yourself, there are some useful files here.

## bandera: URI support ##


bandera-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bandera-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your banderaqt binary to `/usr/bin`
and the `../../share/pixmaps/bandera128.png` to `/usr/share/pixmaps`

bandera-qt.protocol (KDE)

