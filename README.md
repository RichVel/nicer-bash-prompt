nicer-bash-prompt
=================

Create a nicer bash prompt including red prompt on production hosts, current
git branch, and the last two directories in $PWD.

Screenshot: ![screenshot of red prompt](http://i.imgur.com/aLbWw3Z.png)

It's completely driven by hostname so as long as you have a suitable pattern to
production hostnames (e.g. xyprod01, 02, etc) it will work well, and you can
use the same .bashrc in all environments.

Includes optional feature to sync your bash history across all terminal
windows.  This is nice but not everyone wants it, so it's disabled by default.

Installation
============

Include this in your .bashrc - it's not a complete bashrc, so just append it to
the end of the .bashrc file.

Be sure to first comment out any previous PS1 settings - get this working
first, then you can customize to fit.

Look for the CUSTOMIZE comments to configure for your hostnames, domain name,
and so on.


Testing
=======

Most of the code works on non-production hosts.

To show the red prompt on any host, use `export SIMULATE_PROD=yes`. 

Use `unset SIMULATE_PROD` to clear this.
