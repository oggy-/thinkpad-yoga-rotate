thinkpad-yoga-rotate
====================

A small utility script to automatically rotate the screen of Thinkpad Yoga in Linux, when switching to or from the tablet mode. Relies on acpid and xrandr. 

The Arch Linux package is in the subfolder, and also available on AUR as thinkpad-yoga-rotate. You need to restart acpid after installing the package.

For non-Arch users:
  - copy `tablet-mode` into `/etc/acpi/events`
  - copy `rotate-screen.sh` into `/etc/acpi/actions` and make it executable (`chmod +x /etc/acpi/actions/rotate-screen.sh`)
  - restart acpid

**Note**: this package assumes that the Wacom input is automatically rotated with the screen. This seems to be the case with Gnome 3.12 by default, and can be set in KDE using kcm-wacomtablet.
