# German Colemak Layout

For Linux using Xorg

xmodmap modifies existing keys, so I just modified the official xmodmap by removing everything but the A-Z characters

https://colemak.com/Unix

which will therefore not change the existing (german) special characters

**this is a beta version**

## Umlaute

ä, Ä, ü and Ü stay where they are

ö and Ö moved to:

AltGr+q and AltGr+Shift+Q

## Usage

```
setxkbmap de; xmodmap xmodmap.colemak.de
```

to switch back, use

```
setxkbmap de
```

## Useful Links and Commands

layout of xmodmap files:

https://wiki.archlinux.org/index.php/Xmodmap

using xev to get keycodes:

https://unix.stackexchange.com/a/49651

get your current keycode assignment:

```
xmodmap -pke 
```

