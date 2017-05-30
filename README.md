# arch-bootstrap
Bootstrap ArchLinux build

Downloads and extracts the "bootstrap" ArchLinux distribution (used for
initializing an ArchLinux install from an existing Linux installation).

The bootstrap build contains *no* text editors, so it is recommended that
the `base` package is installed, as in the devjump/arch-base image,
however, you are free to install the packages you wish!

Requires Docker 17.05+ to build.

```
docker build -t arch-bootstrap .
```
