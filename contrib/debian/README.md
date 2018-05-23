
Debian
====================
This directory contains files used to package luqd/luq-qt
for Debian-based Linux systems. If you compile luqd/luq-qt yourself, there are some useful files here.

## luq: URI support ##


luq-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install luq-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your luqqt binary to `/usr/bin`
and the `../../share/pixmaps/luq128.png` to `/usr/share/pixmaps`

luq-qt.protocol (KDE)

