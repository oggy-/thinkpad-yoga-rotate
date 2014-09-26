thinkpad-yoga-rotate
====================

A small utility script to automatically rotate the screen of Thinkpad Yoga in Linux, when switching to or from the tablet mode. Relies on acpid and xrandr. 

The Arch Linux package is in the subfolder. For non-Arch users, just copy:
  - `tablet-mode` into `/etc/acpi/events`
  - `rotate-screen.sh` into `/etc/acpi/actions`

**Note**: this package assumes that the Wacom input is automatically rotated with the screen. This seems to be the case with Gnome 3.12 by default, and can be set in KDE using kcm-wacomtablet.
