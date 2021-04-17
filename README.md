# Since the beginning of 2021 I play a little more with Arch Linux #

Since I often build a new machine to test different configurations and startover with a clean install afterwards, it makes sense to put an installation script on Github.

After booting from the Arch Linux USB stick, an automated installation can be done very easily.
The install will only take around 1 - 2 minutes with a fast internet connection.

Only 5 manual commands are necessary.
In between you will be asked for the password of the user peter (can be changed in the script) and root.

Becareful to check the script before executing as it complete erases the ssd and partitions and format the drives.

You can of course use it for your own configuration and adapt the skript.

Commands

loadkeys de-latin1
pacman -Sy git
git clone https://github.com/peterleimbach/simplearchinstall
cd simplearchinstall
sh install

