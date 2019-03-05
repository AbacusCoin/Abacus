
Debian
====================
This directory contains files used to package abad/aba-qt
for Debian-based Linux systems. If you compile abad/aba-qt yourself, there are some useful files here.

## aba: URI support ##


aba-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aba-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your abaqt binary to `/usr/bin`
and the `../../share/pixmaps/aba128.png` to `/usr/share/pixmaps`

aba-qt.protocol (KDE)

