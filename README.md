# Daerck's fork of [dmenu](https://tools.suckless.org/dmenu/).

## Patches

- [center](https://tools.suckless.org/dmenu/patches/center/).
- [fuzzyhighlight](https://tools.suckless.org/dmenu/patches/fuzzyhighlight/).
- [fuzzymatch](https://tools.suckless.org/dmenu/patches/fuzzymatch/).
- [grid](https://tools.suckless.org/dmenu/patches/grid/).
- [gridnav](https://tools.suckless.org/dmenu/patches/gridnav/).
- [mousesupport](https://tools.suckless.org/dmenu/patches/mouse-support/).

## Installation guide

### Dependency

This build of dmenu does not block the rendering of color emoji, so you must install [libxft-bgra](https://gitlab.freedesktop.org/xorg/lib/libxft), otherwise dmenu will crash upon trying to render one.

After all the dependencies are installed:

```
git clone https://github.com/Daerckdev/dmenu
cd dmenu
sudo make clean install
```
