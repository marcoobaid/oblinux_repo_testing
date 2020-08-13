# OBLinux Testing Repo

### Changes to Packages

local and dconf have been moved into their indavidual packages for xfce.

gimp, conky and root have been moved into their own packages.



Packages
------


------


Instructions
------

Edit your `/etc/pacman.conf` and add the block below at the bottom of your file:

```
	[oblinux_repo_testing]
	SigLevel = Optional TrustedOnly 
	Server = https://marcoobaid.github.io/$repo/$arch

```
