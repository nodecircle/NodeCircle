
Debian
====================
This directory contains files used to package nodecircled/nodecircle-qt
for Debian-based Linux systems. If you compile nodecircled/nodecircle-qt yourself, there are some useful files here.

## nodecircle: URI support ##


nodecircle-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nodecircle-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nodecircleqt binary to `/usr/bin`
and the `../../share/pixmaps/nodecircle128.png` to `/usr/share/pixmaps`

nodecircle-qt.protocol (KDE)

