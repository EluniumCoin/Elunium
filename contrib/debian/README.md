
Debian
====================
This directory contains files used to package eluniumd/elunium-qt
for Debian-based Linux systems. If you compile eluniumd/elunium-qt yourself, there are some useful files here.

## elunium: URI support ##


elunium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install elunium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eluniumqt binary to `/usr/bin`
and the `../../share/pixmaps/elunium128.png` to `/usr/share/pixmaps`

elunium-qt.protocol (KDE)

