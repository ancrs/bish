
Debian
====================
This directory contains files used to package bishd/bish-qt
for Debian-based Linux systems. If you compile bishd/bish-qt yourself, there are some useful files here.

## bish: URI support ##


bish-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bish-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bish-qt binary to `/usr/bin`
and the `../../share/pixmaps/bish128.png` to `/usr/share/pixmaps`

bish-qt.protocol (KDE)

