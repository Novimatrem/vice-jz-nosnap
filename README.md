# vice-jz-nosnap v6

Required packages: sudo, curl, squashfs-tools

Also required (may have to download using web browser and install from package file manually): libreadline7

Required tweaks: Your user must be in the sudoers file.

# Changelog:
- v1 initial working launch

- v2 fixed sound by not running vice as root

- v3 fixed drives by actually copying all required deps

- v4 updated text to mention the required packages to install/tweak needed

- v5 added mention of required packages for functionality

- v6 mention that you may need to manually download and install libreadline7


# Usage: 

```sudo bash ./vice-jz-nosnap.sh```

-all because PCLinuxOS doesn't do snaps, and other, newer, versions of Vice are very slow.
