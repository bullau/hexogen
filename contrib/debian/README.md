
Debian
====================
This directory contains files used to package hexogend/hexogen-qt
for Debian-based Linux systems. If you compile hexogend/hexogen-qt yourself, there are some useful files here.

## hexogen: URI support ##


hexogen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hexogen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hexogen-qt binary to `/usr/bin`
and the `../../share/pixmaps/hexogen128.png` to `/usr/share/pixmaps`

hexogen-qt.protocol (KDE)

