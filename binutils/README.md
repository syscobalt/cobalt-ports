# binutils
## How do I build binutils for Cobalt?
To build binutils for cobalt, simply get the source code of `cobalt-binutils`, change directory to it, and run:
```./configure --host=x86_64-cobalt```
After that, simply run `make`. This should successfully build binutils for Cobalt. After that, you can find the binaries in the subfolder called `binutils`. These binaries only run successfully in Cobalt.
