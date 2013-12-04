# tcolorbox

A crude Debian package for [tcolorbox][]

The LaTeX class [tcolorbox][] that comes with Debian 7 has some
deficiencies. This up-to-date version of the class fixes these.

This package is built from an existing file tree along the lines of
this [guide on askubuntu.com][guide].

## Build

Build the package simply by using make:

    make

## Install 

Install using the normal Debian package installation command:

    dpkg -i tcolorbox_2.51-1_all.deb

[tcolorbox]: http://www.ctan.org/pkg/tcolorbox
[guide]: http://askubuntu.com/questions/146343/how-to-create-a-deb-package-that-installs-a-series-of-files


