# touchup

A shell script used to update various types of packages on Debian-based systems at the same time. The script also cleans many often forgotten corners of the Linux system, making it usefull for troubleshooting.

#### To install:

$ ```sudo false ; wget -L https://github.com/ceresisonline/touchup/blob/7797d781b48068dde0c795a5f0cdaa56019da782/touchup ; sudo chmod +x touchup ; sudo mv touchup /usr/bin/touchup```

#### Known Issues:
- The script can only be called using sudo
- The built-in OMZ updater is currenty not working
- Arch/RedHat/MacOS support will maybe be added in the future. For now only Debian-based systems are supported.
