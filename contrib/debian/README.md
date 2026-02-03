
Debian
====================
This directory contains files used to package nakamd/nakam-qt
for Debian-based Linux systems. If you compile nakamd/nakam-qt yourself, there are some useful files here.

## nakam: URI support ##


nakam-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nakam-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nakam-qt binary to `/usr/bin`
and the `../../share/pixmaps/nakam128.png` to `/usr/share/pixmaps`

nakam-qt.protocol (KDE)

