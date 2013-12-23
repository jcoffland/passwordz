passwordz
=========

A password manager for Gnome keyrings

installation
============

On debian based systems install the following:

    sudo apt-get install python-gtk2 python-keyring

Then install like this:

    sudo cp passwordz passwordz.glade /usr/local/bin/
    sudo chmod +x /usr/local/bin/passwordz

And run like this:

    passwordz

usage
=====

Double click keyrings to unlock and relock.  Right click to bring up keyring
menu.  Double click passwords to copy to clipboard.  Middle click to paste
password.  Keyrings will autolock after a configurable timeout.
