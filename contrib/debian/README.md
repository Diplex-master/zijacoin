
Debian
====================
This directory contains files used to package diplexcoind/diplexcoin-qt
for Debian-based Linux systems. If you compile diplexcoind/diplexcoin-qt yourself, there are some useful files here.

## diplexcoin: URI support ##


diplexcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install diplexcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your diplexcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/diplexcoin128.png` to `/usr/share/pixmaps`

diplexcoin-qt.protocol (KDE)

