passwordz
=========

A password manager for Gnome keyrings.

Features:

* Stores passwords securely using Gnome keyrings.
* Provides quick access to passwords in a simple interface.
* Copies passwords to clipboard without ever displaying them on screen.
* Automatically clears clipboard after timeout.
* Automatically locks keyrings after configurable timeout.
* Drag and drop passwords to move between keyrings.
* Automatically locks all keyrings opened in passwordz on exit.
* Passwords and keyrings are sorted in lexicographical order.
* Allows user to easily delete the 'login' keyring so keyrings stay locked
  after reboot


installation
============

On Debian systems install the following:

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
password.
