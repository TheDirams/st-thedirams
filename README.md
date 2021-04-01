# TheDirams's fork of st (Simple Terminal)

[st](https://st.suckless.org/) is one of the best and minimalist
terminal emulator on linux

## Bindings

+ `Alt+Shift+K`     zoom-in
+ `Alt+Shift+J`     zoom-out
+ `Alt+Shift+Space` zoom-reset
+ `Alt+c`           copy
+ `Alt+p`           paste

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

## Update 
This build uses NerdFont for Glyphs.
