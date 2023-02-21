# zlib
## About
zlib isn't a port since it is compatible with Cobalt's cross compiler.
## How to build
to build zlib, simply download the zlib source code (tested on version 1.2.13), edit `Makefile.in`, and set CC to either `i686-cobalt-gcc` (if you're on a IA-32 system) or `x86_64-cobalt-gcc` (if you're on a x86_64 system)
