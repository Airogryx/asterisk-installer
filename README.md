# Asterisk Installer Script

This script automates the installation of Asterisk PBX on Ubuntu systems. It handles dependency installation, downloading, compiling, and configuring Asterisk.

## Features

- Automated installation of Asterisk PBX.
- Dependency management.
- Internet connection check.
- Checks for existing Asterisk installation.
- Clean up temporary files.
- Clear progress messages.
- Installation of sample configuration files.
- Enables and restarts the Asterisk service.

## Prerequisites

- Ubuntu operating system.
- Root privileges (sudo).
- Internet connection.

## Usage

1. Clone the repository: `git clone https://github.com/Airogryx/asterisk-installer.git`
2. Navigate to the repository directory: `cd asterisk-installer`
3. Make the script executable: `chmod +x install.sh`
4. Run the script with root privileges: `sudo ./install.sh`


## Script Details

- **Asterisk Version**: Installs the latest stable version of Asterisk.
- **Installation Directory**: Installs Asterisk in `/usr/local/src`.
- **Cleanup**: Removes temporary files after installation.
- **Service**: Enables and restarts the asterisk service.

## Notes

- This script is designed specifically for Ubuntu.
- The script checks for an internet connection before proceeding.
- The script will exit if Asterisk is already installed.
- The script must be run as root.
- The script will install the latest stable version of Asterisk.
