
Debian
====================
This directory contains files used to package dashdiffd/dashdiff-qt
for Debian-based Linux systems. If you compile dashdiffd/dashdiff-qt yourself, there are some useful files here.

## dashdiff: URI support ##


dashdiff-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dashdiff-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dashdiff-qt binary to `/usr/bin`
and the `../../share/pixmaps/dashdiff128.png` to `/usr/share/pixmaps`

dashdiff-qt.protocol (KDE)

