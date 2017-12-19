META-PELUX
==========
A Yocto/OpenEmbedded layer providing PELUX images. PELUX is a Linux based platform used for developing automotive infotainment projects.

The layer provides the PELUX distro that is derived from poky. Furthermore, this layer provides `core-image-pelux` recipes, along with necessary additions to software components to enable a functional In-Vehicle Infotainment (IVI) base image. The software component additions and appendments found in this layer are specific for the PELUX image but can be used outside of this context. 

Maintained at https://github.com/pelagicore/meta-pelux

Dependencies
------------

This layer depends on:
* poky (http://git.yoctoproject.org/cgit/cgit.cgi/poky)
* meta-openembedded (http://cgit.openembedded.org/meta-openembedded/)
* meta-virtualization (http://git.yoctoproject.org/cgit/cgit.cgi/meta-virtualization), if the "process-containment" distro feature has been enabled
* meta-bistro (https://github.com/Pelagicore/meta-bistro)

Branching
---------
This repository will follow the yocto release system. Whenever a new yocto release has been released, a new branch with the same name will be created from the master branch. All feature growth should happen first on the master branch, but will also be cherry picked back to the latest yocto release branch. Security and bug fixes will be evaluated case by case and backported as necessary. The ambition is to actively maintain the two latest releases and/or one year old releases in this fashion.

License and Copyright
---------------------
Copyright (C) 2016-2017 Pelagicore AB

All metadata is MIT licensed unless otherwise stated. Source code included in tree for individual recipes is under the LICENSE stated in the associated recipe (.bb file) unless otherwise stated.

License information for any other files is either explicitly stated or defaults to MIT license.
