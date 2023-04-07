# Datagrip AUR Package for Arch Linux

This repository contains an Arch User Repository package for Datagrip, a powerful database IDE for SQL developers. The binary for this package is downloaded from the official Jetbrains website and then packaged for installation on Arch Linux.

This package follows a specific standard for installation:

- Application files directory: `/usr/share/jetbrains-datagrip`
- Executable Datagrip directory: `/usr/bin/datagrip`
- Desktop file directory: `/usr/share/applications`

The executable in `/usr/bin` is installed as a symbolic link to the Datagrip binary inside the application files. The desktop file is installed in `/usr/share/applications` so that it can be accessed from the application launcher.

## Notes

This package may differ from the "official" package in the AUR repository in the directories used for installation and the installation steps. The purpose of this package, and others in this account, is to install all the programs that I use following a certain standard (i.e. using `/usr/share/{pkgname}` for application files and `/usr/bin/{execname}` for the executable) and in some cases, clean the installation steps from some bloat.

Feel free to reach out if you have any questions or concerns about this package.
