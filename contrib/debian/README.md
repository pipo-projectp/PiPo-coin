
Debian
====================
This directory contains files used to package pipocoind/pipocoin-qt
for Debian-based Linux systems. If you compile pipocoind/pipocoin-qt yourself, there are some useful files here.

## pipocoin: URI support ##


pipocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pipocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pipocoinqt binary to `/usr/bin`
and the `../../share/pixmaps/pipocoin128.png` to `/usr/share/pixmaps`

pipocoin-qt.protocol (KDE)

