*som_pak*
=========

Repo for ArchLinux packaging of *som_pak*

History
-------

I coded this because I needed to use *som_pak* for a course I did at uni and I thought it would help others in the class out who needed the program. As I have no interest in continuing to maintain this, I decided against publishing it to AUR. If you are interested in maintaining it you are most welcome to fork the repo and post it to AUR.

Installation
------------

If you are just trying to install som_pak on your Arch machine. The simplest is to download a ZIP of the repo (or if you prefer use Git) and then run from the directory containing `PKGBUILD` and the patch run:

    makepkg -c
    makepkg -s
    makepkg -i


Uninstalling
------------

    pacman -Rs som_pak

License
-------

*som_pak* code (not included in the repo but automatically downloaded by `makepkg`) comes with the following license:

    ************************************************************************
    *                                                                      *
    *  NOTE: This program package is copyrighted in the sense that it      *
    *  may be used for scientific purposes. The package as a whole, or     *
    *  parts thereof, cannot be included or used in any commercial         *
    *  application without written permission granted by its producents.   *
    *  No programs contained in this package may be copied for commercial  *
    *  distribution.                                                       *
    *                                                                      *
    *  All comments concerning this program package may be sent to the     *
    *  e-mail address 'som@nucleus.hut.fi'.                                *
    *                                                                      *
    ************************************************************************
