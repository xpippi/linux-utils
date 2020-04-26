# add-favorite.sh

This is a script for Gnome users that can 'favorite', or pin, an application if you don't see the option to do so when right-clicking the application's taskbar button.  I encounter this more than I'd want to, so I created this script to automate the process.

You'll need to create a .desktop launcher and then provide it as a command-line argument to the script.  The script will take care of the rest.  For information on how to create a launcher, see https://askubuntu.com/a/64237.

The script has two modes of adding a favorite:  either "installing" or not installing the launcher.  Installing a launcher (by using the optional --install flag) will move the specified launcher to /home/[you]/.local/share/applications.  This option is intended to be used with launchers you create yourself and would therefore want to restore from a backup if the need should arise.  It will then offer to create a symlink to it in /usr/share/applications if you want to share it with other accounts.


# require

A helper script to check for script dependencies


# update-thunderbird.sh

Upgrades Thunderbird to the latest version.  This is applicable if you don't manage Thunderbird via a package manager.


# yesno

A helper script to display a configurable yes/no prompt