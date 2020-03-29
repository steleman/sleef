# sleef
fork of SLEEF https://sleef.org/

This is my fork of SLEEF. It contains some improvements to the build system that make it easier to build.

See the file Makefile.build-sleef in the toplevel of each SLEEF source directory. You can use this Makefile to build SLEEF.

How to use:

- Copy this Makefile to the directory above the SLEEF source code directory.
- gmake -f Makefile.build-sleef configure > configure.out 2>&1
- gmake -f Makefile.buidl-sleef build > build.out 2>&1

The Makefile is configured to use a default installation of GCC as it can be found on any Linux distro. It should work out of the box on X86_64 and AArch64.
