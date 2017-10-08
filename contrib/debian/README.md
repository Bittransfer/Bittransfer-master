
Debian
====================
This directory contains files used to package bittransferd/bittransfer-qt
for Debian-based Linux systems. If you compile bittransferd/bittransfer-qt yourself, there are some useful files here.

## bittransfer: URI support ##


bittransfer-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bittransfer-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bittransferqt binary to `/usr/bin`
and the `../../share/pixmaps/bittransfer128.png` to `/usr/share/pixmaps`

bittransfer-qt.protocol (KDE)

