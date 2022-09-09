# touchup

A shell script used to update various types of packages at the same time on Debian, Arch, or MacOS. The script also cleans many often forgotten corners of the Linux system, making it useful for troubleshooting.

If there's absolutely nothing to install, touchup should be quiet except for a start and stop dialogue. To show extra information, run touchup with the debug flag "-d".

![Screenshot from 2022-08-23 22-26-01](https://user-images.githubusercontent.com/39637438/186305908-8184214d-7f91-498c-93cb-df18ae42dfe1.png)
#### To install on Linux:

	sudo false
	wget https://raw.githubusercontent.com/sq1000000/touchup/main/touchup
	sudo chmod +x touchup
	sudo mv touchup /usr/bin/touchup

#### To install on MacOS:

	sudo false
	wget https://raw.githubusercontent.com/sq1000000/touchup/main/touchup
	sudo chmod +x touchup
	sudo mv touchup /opt/homebrew/bin/touchup

#### To run:

	sudo touchup
	
#### To run with debug output:
	
	sudo touchup -d

![Screenshot from 2022-08-23 22-25-25](https://user-images.githubusercontent.com/39637438/186306182-f4422d39-4bba-445c-9eff-fa0a65e5f8c4.png)

#### Known Issues:
- Cargo, Pip3, and Zeek updates don't happen. This will hopefully be fixed very soon
- Support for emptying trash and omz updates doesn't exist for MacOS. This might not be fixable. I'm working on it.
- Support for dnf, yum, & rpm will maybe be added in the future. For now this script can only utilize apm, apt-get, aptitude, betterdiscordctl, brew, cargo, flatpak, fwupdmgr, grub, npm, pacman, pip3, snap, tldr, yay, & zeek
