# Kernel_Manager

A simple set of sripts using zenity to help organize them.
This set of scripts is meant to help manage custom kernel builds.
You can sync with upstream, push your changes to your personal repo, build the kernel,
install, sign the kernel and modules, and even reboot. 

Some functions require root password, so I have included a password prompt in most cases.

This is designed to run in gnome terminal and is built for debian based builds.
    There are plans to introduce other terminals.

Installation and Usage
    Download latest release (see below) and install via normal .deb install process
    If your linux distro does not support .deb, you can always clone the repo and manually install the binary and 
    icon. Place binary in /usr/local/bin and the icon in /usr/share/applications.
        App can be executed straight from menu->programming->LZ-Kernel-Manager or in terminal with `lzkm`. Since there is a password prompt, there is no need to execute with sudo.

**Releases are in .deb format.**
Download the latest release here https://github.com/TeamFahQ/lz_kernel_manager/tree/master/Releases

Please don't hesitate to post any issues. For features and suggestions, you can use the issues but please add 
**[FEATURE REQUST]** to your title.

