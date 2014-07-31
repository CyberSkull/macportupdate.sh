macportupdate.sh
================

Simple script to update MacPorts and remove old versions

This script runs several commands for a plain vanilla setup of MacPorts.

* `port selfupdate` - MacPort updates itself.
* `port list outdated` - Prints a list of outdated programs.
* `port upgrade outdated` - Updates the outdated programs.
* `port uninstall inactive` - Uninstalls the inactive (old) versions.

Installation: Drop it wherever you wish in your `$PATH`. I keep my in `~/bin/macportupdate.sh`.
To use, just run `sudo macportupdate.sh`.
