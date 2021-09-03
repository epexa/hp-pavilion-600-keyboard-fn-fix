# HP Pavilion 600 Keyboard FN Fix

## For Linux:

### Autostart:

1. Copy [.Xmodmap](.Xmodmap) file to `~/` (or to any location)
2. Add command to autostart: `xmodmap ~/.Xmodmap`

### Or manual in terminal:
```bash
xmodmap -e 'keysym XF86AudioMute = F1'
xmodmap -e 'keycode 67 = XF86AudioMute'

xmodmap -e 'keysym XF86AudioLowerVolume = F2'
xmodmap -e 'keycode 68 = XF86AudioLowerVolume'

xmodmap -e 'keysym XF86AudioRaiseVolume = F3'
xmodmap -e 'keycode 69 = XF86AudioRaiseVolume'

xmodmap -e 'keysym XF86AudioPrev = F4'
xmodmap -e 'keycode 70 = XF86AudioPrev'

xmodmap -e 'keysym XF86AudioPlay = F5'
xmodmap -e 'keycode 71 = XF86AudioPlay'

xmodmap -e 'keysym XF86AudioNext = F6'
xmodmap -e 'keycode 72 = XF86AudioNext'

xmodmap -e 'keysym XF86MonBrightnessDown = F7'
xmodmap -e 'keycode 73 = XF86MonBrightnessDown'

xmodmap -e 'keysym XF86MonBrightnessUp = F8'
xmodmap -e 'keycode 74 = XF86MonBrightnessUp'

xmodmap -e 'keysym XF86TouchpadToggle = F12'
xmodmap -e 'keycode 96 = XF86TouchpadToggle'
```

### Reset:
```bash
setxkbmap
```

## For Windows:

https://github.com/evgeny-gist/hpKeyboard800
