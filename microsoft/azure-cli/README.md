# Azure CLI AUR Package for Arch Linux

This repository contains an Arch User Repository package for Azure CLI, a set of command-line tools for Azure management. This package installs the Azure CLI using Python's virtual environment.

This package follows a specific standard for installation:

- Application files directory: `/usr/share/azure-cli`
- Executable az file: `/usr/bin/az`

## Installation

The installation process for the Azure CLI package involves:

- Creating the necessary directories
- Setting the installation directory
- Creating a python virtual environment
- Installing Azure CLI using pip
- Installing the completion script
- Creating a symbolic link to the `az` executable

## Notes

This package may differ from the "official" package in the AUR repository in the directories used for installation and the installation steps. The purpose of this package, and others in this account, is to install all the programs that I use following a certain standard (i.e. using `/usr/share/{pkgname}` for application files and `/usr/bin/{execname}` for the executable) and in some cases, clean the installation steps from some bloat.

Feel free to reach out if you have any questions or concerns about this package.
