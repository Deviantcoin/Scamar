
Debian
====================
This directory contains files used to package scamard/scamar-qt
for Debian-based Linux systems. If you compile scamard/scamar-qt yourself, there are some useful files here.

## scamar: URI support ##


scamar-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install scamar-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your scamarqt binary to `/usr/bin`
and the `../../share/pixmaps/scamar128.png` to `/usr/share/pixmaps`

scamar-qt.protocol (KDE)

