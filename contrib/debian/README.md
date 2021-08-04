
Debian
====================
This directory contains files used to package socialcoind/socialcoin-qt
for Debian-based Linux systems. If you compile socialcoind/socialcoin-qt yourself, there are some useful files here.

## socialcoin: URI support ##


socialcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install socialcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your socialcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

socialcoin-qt.protocol (KDE)

