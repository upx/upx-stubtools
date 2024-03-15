                 ooooo     ooo  ooooooooo.  ooooooo  ooooo
                 `888'     `8'  `888   `Y88. `8888    d8'
                  888       8    888   .d88'   Y888..8P
                  888       8    888ooo88P'     `8888'
                  888       8    888           .8PY888.
                  `88.    .8'    888          d8'  `888b
                    `YbodP'     o888o       o888o  o88888o


                    The Ultimate Packer for eXecutables
                           https://upx.github.io



UPX STUB TOOLS
==============

Download: https://github.com/upx/upx-stubtools/releases


USAGE
=====

These tools are needed to rebuild the UPX stubs from source code, using
a Podman/Docker container running an Ubuntu-22.04 image.

For detailed usage instructions see

https://github.com/upx/upx/tree/master/misc/podman/rebuild-stubs


OVERVIEW
========

This archive contains a number of cross-compilers and other tools,
pre-compiled for a amd64-linux development platform.

These tools are needed for rebuilding the UPX stubs, and the main reason
for providing these binaries is that this way all UPX developers will
produce byte-identical results.

Here is an overview of the included packages including links where you
can get the full source code and more information:

Package         License     URL
-------         -------     ---
clang           Apache-2.0  https://llvm.org/
crosstool       GNU GPL     http://kegel.com/crosstool/
djasm           GNU GPL     http://www.delorie.com/djgpp/
GNU binutils    GNU GPL     https://www.gnu.org/software/binutils/
GNU gcc         GNU GPL     https://gcc.gnu.org/
llvm            Apache-2.0  https://llvm.org/
sstrip          GNU GPL     https://www.muppetlabs.com/~breadbox/software/


Share and Enjoy,
Markus

   Markus F.X.J. Oberhumer
   <markus@oberhumer.com>


CHANGELOG
=========

Changes in v20221212 (12 Dec 2022):
  * add clang-format-15.0.6
  * remove clang-3.9.0

Changes in v20210104 (04 Jan 2021):
  * add clang-format-10.0.1
