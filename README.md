GBDK
====

"The GameBoy Developer's Kit (GBDK), is a set of tools that enable to
develop programs for the Nintendo GameBoy system, either in C or in
assembly. GBDK includes a set of libraries for the most common
requirements and generates image files for use with a real GameBoy or
with an emulator like VGB or no$gmb. [...]

GBDK features:
  * An ANSI C compiler.
  * An assembler that generates relocatable code.
  * A peephole optimiser.
  * A linker that produces GameBoy image files.
  * Support for multiple-bank images.
  * Smart linking.
  * A set of libraries, with source code.
  * Example programs in assembly and in C."

From http://gbdk.sourceforge.net

Quick summary
=============

The base version (2.96a) was downloaded from the official site. Although
this is the latest version, it was released quite a while ago (back in
April 2002).

Unfortunately the code could not be compiled with an up-to-date setup.
Also, compiling to 64-bit systems fails.

The aim of this repository is to make the GBDK compatible with the
latest compilers (gcc 4.6, 4.7), to include all dependencies needed for
the compilation, and to have pre-built binaries as well as packages for
today's popular operating systems like Ubuntu, Debian and Windows. I am
writing this in 2013, I am curious what will this project look like in
2024 :)

Having a simple build system (downloading and installing dependencies,
running builds, creating packages - all scripted) and using a Continous
Integration tool like Travis CI would be nice though.

Original sites:
  * http://gbdk.sourceforge.net
  * http://sourceforge.net/projects/gbdk
