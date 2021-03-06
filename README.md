# Simple Terminal

A simple virtual terminal emulator for X.

## Table of Contents

* [Installation](#installation)
  * [AUR](#aur)
  * [Manual](#manual)
* [Keymaps](#keymaps)
* [Patches](#patches)

## Installation

### AUR

Install the AUR package with your favorite AUR helper (yay in this case):

```sh
yay --sync "utilyre-st-git"
```

### Manual

Install these packages:

1. git
2. make
3. libxft-bgra

Clone the repository:

```sh
git clone "https://github.com/utilyre/st.git"
```

Change directory to the repo and run the command below:

```sh
sudo make install
```

## Keymaps

* **Copy**: `Ctrl + Shift + C`
* **Paste**: `Ctrl + Shift + V`
* **Zoom**: `Ctrl + Shift + Page Up`
* **Unzoom**: `Ctrl + Shift + Page Down`
* **Reset zoom**: `Ctrl + Shift + Page Home`

## Patches

1. [alpha](https://st.suckless.org/patches/alpha)
2. [glyph wide support](https://st.suckless.org/patches/glyph_wide_support)
3. [ligatures](https://st.suckless.org/patches/ligatures)
4. [xresources](https://st.suckless.org/patches/xresources)
5. [fix keyboard input](https://st.suckless.org/patches/fix_keyboard_input)
6. [swapmouse](https://st.suckless.org/patches/swapmouse)
