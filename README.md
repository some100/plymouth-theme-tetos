# Plymouth Theme TetOS

## Description

A theme for Plymouth boot screens, inspired by the boot screen in [Machine Love](https://www.youtube.com/watch?v=sqK-jh4TDXo).

Also supports custom dialog screens for passwords, firmware upgrades, updates, shutting down, and rebooting. It also has a progress bar.

## Preview

![boot screen showing two stage boot process, with progress bar on second stage](preview.gif)

## Installation

Place the contents of this repo in `/usr/share/plymouth/themes/tetos`, then use `plymouth-set-default-theme tetos` as root. On Ubuntu specifically, you need to use `update-alternatives --config default.plymouth` as root.

Afterwards, you can [preview the theme](https://wiki.archlinux.org/title/Plymouth#Preview_themes), then afterwards rebuild the initrd, so that changes will take effect. Before rebuilding the initrd, you should probably remove the preview gif so that the initrd image does not get bloated.

## Credits

* fusorf for making a nearly perfect [recreation](https://www.reddit.com/r/KasaneTeto/comments/1ius365/remade_tetos_wallpaper_4k) of the boot screen, from which I made minor adjustments for accuracy.
* JamieP for making [Machine Love](https://www.youtube.com/watch?v=sqK-jh4TDXo), from which this design originated from. It's an amazing song. Go listen to it.
