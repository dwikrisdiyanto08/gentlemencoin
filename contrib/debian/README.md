
Debian
====================
This directory contains files used to package gentsd/gents-qt
for Debian-based Linux systems. If you compile gentsd/gents-qt yourself, there are some useful files here.

## gents: URI support ##


gents-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gents-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gentsqt binary to `/usr/bin`
and the `../../share/pixmaps/gents128.png` to `/usr/share/pixmaps`

gents-qt.protocol (KDE)

