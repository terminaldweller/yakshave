**_THIS IS A JOKE FORK_**

Yakshave is a fork of Yakuake which is a drop-down terminal emulator based on KDE Konsole technology.

It's a KDE Extragear application released under GPL v2, GPL v3 or any later
version accepted by the membership of KDE e.V.

### Basic build and installation instructions:

1. Download the source code or clone this repository
2. `cd` to the source code folder
3. `mkdir build`
4. `cd build`
5. `cmake ../` - defaults to `/usr/local` as installation path on UNIX ([docs](https://cmake.org/cmake/help/latest/variable/CMAKE_INSTALL_PREFIX.html)), optionally use `-DCMAKE_INSTALL_PREFIX=<path to install to>`
6. `make`
7. `sudo make install`

To remove use `sudo make uninstall`
