nicer-bash-prompt
=================

Create a nicer bash prompt including red prompt on production hosts, current git branch, and last 2 directories in $PWD

Includes optional feature to sync your bash history across all terminal windows.  This is nice but not everyone wants it,
so it's disabled by default.

Installation
============

Include this in your .bashrc - it's not a complete bashrc, so just append it to the end of the .bashrc file.

Be sure to comment out any previous PS1 settings - get this working first, then you can customize

Look for the CUSTOMIZE comments to configure for your hostnames, domain name, and so on.
