# (My) Quantum Mechanical Keyboard Firmware

This is my personal fork of the [QMK
Firmware](https://github.com/qmk/qmk_firmware) that includes my custom
changes and improvements for my personal use. Don't expect much of it.

Currently I'm owning a [Lily58L](keyboards/lily58/light) keyboard so
most likely no changes will be added to any keyboard except that one.

All the changes done on this repo respect the original one are tracked
on the `dx-master`, while the `master` branch will be kept in sync
with the original one from the QMK repo.

Building:

 - `make lily58/light:lily58l:dfu-split-left` for left side.
 - `make lily58/light:lily58l:dfu-split-right` for right side.
