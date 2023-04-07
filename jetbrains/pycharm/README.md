# AUR package for Jetbrains - Pycharm
This repo contains an Arch User Repository package for Jetbrains Pycharm following the next standard for the installation:

1. App files directory: `/usr/share/jetbrains-pycharm`
2. Executable `pycharm` directory: `/usr/bin/pycharm`
3. .desktop file directory: `/usr/share/applications`

* The executable in `/usr/bin` is installed as symbolic link to the `pycharm` bin inside the app files.

## * Notes

This package may differ from the "official" in the AUR repository in the directories used for the installation and the steps used. The purpose of this package and others 
ones in this account is for install all the programs that I used following certain standard (i.e. using `/usr/share/{pkgname}` for app files and `/usr/bin/{execname}`
for executable) and in some cases clean the installation steps from some bloat.
