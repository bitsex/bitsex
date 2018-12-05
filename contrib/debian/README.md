
Debian
====================
This directory contains files used to package bitsexd/bitsex-qt
for Debian-based Linux systems. If you compile bitsexd/bitsex-qt yourself, there are some useful files here.

## bitsex: URI support ##


bitsex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitsex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitsexqt binary to `/usr/bin`
and the `../../share/pixmaps/bitsex128.png` to `/usr/share/pixmaps`

bitsex-qt.protocol (KDE)

