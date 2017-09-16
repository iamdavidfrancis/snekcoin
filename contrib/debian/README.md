
Debian
====================
This directory contains files used to package snekcoind/snekcoin-qt
for Debian-based Linux systems. If you compile snekcoind/snekcoin-qt yourself, there are some useful files here.

## snekcoin: URI support ##


snekcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install snekcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your snekcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

snekcoin-qt.protocol (KDE)

