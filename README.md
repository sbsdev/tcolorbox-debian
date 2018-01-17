# tcolorbox

**DEPRECATED:** This package is no longer maintained. Modern versions of Debian come with an up-to-date [tcolorbox][], so this package is no longer needed. Upgrade your Debian instead of using this package.

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

    dpkg -i tcolorbox_2.51-4_all.deb

## License

The LaTeX package tcolorbox is licensed under
[The LaTeX Project Public License 1.3][llpl]. The Debian packaging is
licensed under the [GNU General Public License version 3][GPL-3+].

[tcolorbox]: http://www.ctan.org/pkg/tcolorbox
[guide]: http://askubuntu.com/questions/146343/how-to-create-a-deb-package-that-installs-a-series-of-files
[llpl]: http://www.ctan.org/license/lppl1.3
[GPL-3+]: http://www.gnu.org/licenses/gpl-3.0.html
