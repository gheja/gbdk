GBDK
====

The GameBoy Developers Kit.

Original sites:
  * http://gbdk.sourceforge.net
  * http://sourceforge.net/projects/gbdk

The base version (2.96a) was downloaded from the official site. As it is
a rather old release (from April 2002) the code could not be compiled
with up-to-date compilers. Also, compiling to 64-bit systems fails.

The aim of this repository is to make the GBDK compatible with the
latest compilers (gcc 4.6, 4.7), to include all dependencies needed for
compilation, and to have prebuilt binaries as well as packages for
popular operating systems like Ubuntu, Debian and Windows. Having a
simple build system and using a Continous Integration tool like Travis
CI would be nice though.

Overview of GBDK
================

From http://gbdk.sourceforge.net

"The GameBoy Developer's Kit (GBDK), is a set of tools that enable to
develop programs for the Nintendo GameBoy system, either in C or in
assembly. GBDK includes a set of libraries for the most common
requirements and generates image files for use with a real GameBoy or
with an emulator like VGB or no$gmb.

[...]

GBDK features:
  * An ANSI C compiler.
  * An assembler that generates relocatable code.
  * A peephole optimiser.
  * A linker that produces GameBoy image files.
  * Support for multiple-bank images.
  * Smart linking.
  * A set of libraries, with source code.
  * Example programs in assembly and in C."
