### Why Openmediavault?
Openmediavault is a linux distribution used as an interface for NAS devices. It provides functionality like SMB, user authentication and authorization, volume management, and system monitoring out of the box. It is highly customizable through Docker and the built-in plugin system. Because it is built on Linux, you can simply SSH into your machine and install whatever you want.

### Tools
These are only necessary for the installation process and may be removed later:
- Thumb drive
- Keyboard
- Monitor

### Installation
1. [Download](https://www.openmediavault.org/download.html) the current ISO image
2. Use a tool like [Rufus](https://rufus.ie/) to create a bootable USB drive
3. To make things easier, unplug all hard drives except the one that the operating system will be installed on
4. Boot into your USB drive. This is usually done by entering the BIOS by pressing DEL at system startup and entering the boot menu.
6. The installation process will begin and ask for your language and keyboard preferences
7. Configure the network: 
    - Hostname: If configured properly, the hostname can be used to access your machine using a url like `http://openmediavault.local`
    - Domain name: I keep the default `local` so that it is obvious that I am on my local network. After installation, with the default settings, I should be able to access OMV's web interface at `http://openmediavault.local` 
8. Set up users and passwords:
    - Root password: Remember this password to access your machine as root in the *system*. This is **different** from the admin account which is used to access the OMV *web interface*.
9. Hopefully, you only have one hard drive device connected, but if not, it will ask you which disk to install OMV on
10. Configure the package manager:
    - The installer will ask you information about where you are located so that you can choose a mirror that is closest to you to download your Debian installation.
11. The system will restart and you can remove your thumb drive
12. The system will boot and display the IP address you can use to access your OMV web interface or you can use the hostname and domain name that you set up before.
13. From a computer on your network, go to your machine's address `http://openmediavault.local` or `http://<IP ADDRESS>/`. The web interface will ask you for your username and password. This is **NOT** the root password that you set up earlier.
    - username: `admin`
    - password: `openmediavault`
14. Network interfaces and SSH should be configured and enabled automatically
15. [OMV Configuration](guides/03-openmediavault-configuration.md) 
