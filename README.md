# patchpkgbuild
Utility for patching Arch Linux PKGBUILDs

Based on [ibrokemypie](https://github.com/ibrokemypie)'s [makeppkg](https://github.com/ibrokemypie/makeppkg)

## Usage
```sh
./patchpkgbuild
# Usage: ./patchpkgbuild <patch file>...
ls
# PKGBUILD my.patch
./patchpkgbuild my.patch
# Saving stock PKGBUILD to PKGBUILD.bak
# Modifying PKGBUILD
makepkg -si
```
