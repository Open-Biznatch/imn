
Debian
====================
This directory contains files used to package imnd/imn-qt
for Debian-based Linux systems. If you compile imnd/imn-qt yourself, there are some useful files here.

## imn: URI support ##


imn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install imn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your imnqt binary to `/usr/bin`
and the `../../share/pixmaps/imn128.png` to `/usr/share/pixmaps`

imn-qt.protocol (KDE)

