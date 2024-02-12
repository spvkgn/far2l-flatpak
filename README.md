[![build](https://github.com/spvkgn/far2l-flatpak/actions/workflows/build.yml/badge.svg)](https://github.com/spvkgn/far2l-flatpak/actions/workflows/build.yml) ![version](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/spvkgn/f53cb6c1d56b0eaf40c88d607fc5fef1/raw/far2l-flatpak.json)
# FAR2L File Manager - Flatpak repo / App bundle
## Install and run
* From repository
```
flatpak remote-add -u --if-not-exists --no-gpg-verify far2l-nightly https://spvkgn.github.io/far2l-flatpak
flatpak install -u -y far2l
flatpak run -u io.github.elfmz.far2l
```
```
flatpak update -u -y io.github.elfmz.far2l
```
* Flatpak app-bundle - [Download](https://github.com/spvkgn/far2l-flatpak/releases/download/latest/io.github.elfmz.far2l.flatpak)
```
flatpak install -u io.github.elfmz.far2l.flatpak
flatpak run -u io.github.elfmz.far2l
```
