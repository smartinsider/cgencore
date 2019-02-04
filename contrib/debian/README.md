
Debian
====================
This directory contains files used to package cgencored/cgencore-qt
for Debian-based Linux systems. If you compile cgencored/cgencore-qt yourself, there are some useful files here.

## cgencore: URI support ##


cgencore-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cgencore-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cgencoreqt binary to `/usr/bin`
and the `../../share/pixmaps/cgencore128.png` to `/usr/share/pixmaps`

cgencore-qt.protocol (KDE)

