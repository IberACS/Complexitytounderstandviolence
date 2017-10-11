
Download for Linux and Unix

It is easiest to install Git on Linux using the preferred package manager of your Linux distribution. If you prefer to build from source, you can find the tarballs on kernel.org.
Debian/Ubuntu

For the latest stable version for your release of Debian/Ubuntu
			
				# apt-get install git

For Ubuntu, this PPA provides the latest stable upstream Git version

				# add-apt-repository ppa:git-core/ppa 
				# apt update; apt install git

Fedora

				# yum install git (up to Fedora 21)
				# dnf install git (Fedora 22 and later)

Gentoo

				# emerge --ask --verbose dev-vcs/git

Arch Linux

# pacman -S git

openSUSE
				
				# zypper install git

Mageia

				# urpmi git

FreeBSD

				# pkg install git

Solaris 9/10/11 (OpenCSW)

				# pkgutil -i git

Solaris 11 Express

				# pkg install developer/versioning/git

OpenBSD

				# pkg_add git

Alpine

				$ apk add git

Red Hat Enterprise Linux, Oracle Linux, CentOS, Scientific Linux, et al.

RHEL and derivatives typically ship older versions of git. You can download a tarball and build from source, or use a 3rd-party repository such as the IUS Community Project to obtain a more recent version of git.
Slitaz

				$ tazpkg get-install git

