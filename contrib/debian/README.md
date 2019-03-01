Debian
======

This directory contains files used to package fotocoind/fotocoin-qt
for Debian-based Linux systems. If you compile fotocoind/fotocoin-qt yourself, there are some useful files here.

## fotocoin: URI support ##

fotocoin-qt.desktop (Gnome / Open Desktop)

To install:

	sudo desktop-file-install fotocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fotocoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/fotocoin128.png` to `/usr/share/pixmaps`

fotocoin-qt.protocol (KDE)