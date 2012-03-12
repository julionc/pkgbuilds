# Arch Linux Packages

This project contains the **PKGBUILDs** of packages I plan to maintain for [Arch Linux](http://www.archlinux.org/) and the [Arch User Repository (AUR)](https://aur.archlinux.org). Contact me with problems/fixes should they arise.

## PKGBUILDs

It contains package descriptions (PKGBUILDs) that allow you to compile a package from source with makepkg and then install it via pacman.

### Installation

AUR installation is normally accomplished through [Yaourt](https://wiki.archlinux.org/index.php/Yaourt):

```
yaourt -Sy webgrind-git
```

However, it can almost be accomplished manually by changing to one of the package directories, building the package, then installing it:

```
makepkg -s
pacman -U webgrind-git-20120311-1-i686.pkg.tar.xz
```

My packages https://aur.archlinux.org/packages.php?SeB=m&K=julionc


