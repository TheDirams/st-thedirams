# TheDirams's fork of st (Simple Terminal)

[st](https://st.suckless.org/) is one of the best and minimalist
terminal emulator on linux

## Bindings

+ `Ctrl+Shift+K`     zoom-in
+ `Ctrl+Shift+J`     zoom-out
+ `Ctrl+Shift+Space` zoom-reset
+ `Ctrl+c`           copy
+ `Ctrl+p`           paste

## Patches

+ Boxdraw
+ Ligatures
+ font2
+ scrollback-mouse
+ vertcenter
+ workingdir

## Installation

```
git clone https://github.com/TheDirams/st-thedirams
cd st-thedirams
sudo make clean install
```

## N.B
If st crashes when displaying emojis/special characters
install [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) from the AUR.
This build of st uses the JoyPixels emojis font, so be sure if it is installed on
your system
