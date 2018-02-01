
Debian
====================
This directory contains files used to package shekeld/shekel-qt
for Debian-based Linux systems. If you compile shekeld/shekel-qt yourself, there are some useful files here.

## shekel: URI support ##


shekel-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install shekel-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your shekelqt binary to `/usr/bin`
and the `../../share/pixmaps/shekel128.png` to `/usr/share/pixmaps`

shekel-qt.protocol (KDE)

