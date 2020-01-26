# Suckless Terminal

My little fork of [st](https://st.suckless.org/) with a few choice patches.

<img src="screenshot.png" width="500vw">

## Patches Applied

  * [alpha](https://st.suckless.org/patches/alpha/) - Opacity of 0.75
  * [anysize](https://st.suckless.org/patches/anysize/)
  * [scrollback](https://st.suckless.org/patches/scrollback/) - Shift + PgUp/PgDn to scroll through terminal history
  * [one clipboard](https://st.suckless.org/patches/clipboard/)

### Other Niceties

  * Dark Pastel Colour Scheme (Stolen from xfce terminal)
  * Two branches - "master" and "x230":
        * "x230" is what I use on my laptop. It has a 1366x768 screen so it has a smaller default font to make up
        for the smaller res.
        * "master" has the larger font for easier reading on my PC with a 1080p screen

## Installation
`git clone https://github.com/Eddie-Jeselnik/st`

`cd st`

`sudo make install`
