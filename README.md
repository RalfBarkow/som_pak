som_pak
=======

Repo for ArchLinux packaging of som_pak

History
-------

I coded this because I needed to use som_pak for a course I did at uni and I thought it would help others in the class out who needed the program. As I have no interest in continuing to maintain this, I decided against publishing it to AUR. If you are interested in maintaining it you are most welcome to fork the repo and post it to AUR.

Installation
------------

If you are just trying to install som_pak on your Arch machine. The simplest is to download a ZIP of the repo (or if you prefer use Git) and then run from the directory containing PKGBUILD and the patch run:

    makepkg -c
    makepkg -s
    makepkg -i


Uninstalling
------------

    pacman -Rs som_pak
