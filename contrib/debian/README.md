
Debian
====================
This directory contains files used to package ziocoind/ziocoin-qt
for Debian-based Linux systems. If you compile ziocoind/ziocoin-qt yourself, there are some useful files here.

## ziocoin: URI support ##


ziocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ziocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ziocoinqt binary to `/usr/bin`
and the `../../share/pixmaps/ziocoin128.png` to `/usr/share/pixmaps`

ziocoin-qt.protocol (KDE)

