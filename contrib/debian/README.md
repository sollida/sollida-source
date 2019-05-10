
Debian
====================
This directory contains files used to package sollidad/sollida-qt
for Debian-based Linux systems. If you compile sollidad/sollida-qt yourself, there are some useful files here.

## sollida: URI support ##


sollida-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sollida-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sollidaqt binary to `/usr/bin`
and the `../../share/pixmaps/sollida128.png` to `/usr/share/pixmaps`

sollida-qt.protocol (KDE)

