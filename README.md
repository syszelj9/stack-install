# stack-install
A shell script that installs the whole webserver stack for you!

<a href="#">
    <img src="https://img.shields.io/badge/version-rewritten-brightgreen.svg" /></a>
<a href="https://github.com/syszelj9/webserver-installer/releases/tag/2.1">
    <img src="https://img.shields.io/badge/latest%20release-2.2-blue.svg" /></a>
    
## Running the script
1. Make sure you are running the script as root. If not, the script will not work. (`sudo su`)
2. Download the installer using `wget https://github.com/syszelj9/stack-install/blob/main/installer.sh`
3. Run the install script by doing `sh installer.sh`
4. MAKE SURE TO FULLY READ EVERYTHING ON SCREEN. IF YOU ENTER AN INVALID OPTION, THE SCRIPT WILL EXIT
5. Enter the required information
6. everything you have selected will be installed

## Video tutorial
- Here is a video tutorial on how to install and run this script.
- Coming soon I promise

## Compatible systems list
| Operating system | Version | Support |
| ---------------- | ------- | ------- |
| Ubuntu | 22.04 LTS | ✅ |
|        | 20.04 LTS | ✅ |
|        | 18.04 LTS | ✅ |
| Debian | 11 | 🔜 |
|        | 10 | 🔜 |
|        | 9  | 🔜 |
|        | 9 | ❌ |
| CentOS | 8 | ❌ |
|        | 7 | ❌ |

*Note: This script can run on Debian based systems but some phpMyAdmin problems may occur. It is suggested to wait for an official Debian release.*

## Requirements
- 64-bit OS
- Internet

## History:
*2.2 Release (Rewritten)*
- Completely rewritten script
- More support coming soon

*2.0 Release*
- Renamed repository from `lampserver-installer` to `webserver-installer`
- Added a menu with more options
- Added NGINX stack support
- Added individual options
- Integrated SSL script into the main menu 

*1.1 Release*
- Fully automated setup
- SSL addon added

*1.0 Pre Release*
- Somewhat automated LAMP install script
