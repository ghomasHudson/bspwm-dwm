# bspwm-dwm
Things to make bwpsm behave like dwm's master/stack layout. Based heavily on the work of [ortango](https://gist.github.com/ortango/398e8404b031e2990597575f0560618f).

![Demo](https://user-images.githubusercontent.com/13795113/76475195-067a3b80-63f6-11ea-9458-0767a00863d7.gif)


# Implementation Status
- [x] Basic master stack
- [x] Adjusting split position
- [x] Promoting window to master
- [x] Moving focus up/down stack
- [x] Swapping windows up/down stack with `Super + Shift + j/k`

# Current key combos
Note: these only contain bspwm-specific sxhkd keybindings. I usually run another sxhkd instance for general bindings (e.g. opening programs)
| Key | Description |
|-----|-------------|
| Super + q | Close window |
| Super + j/k | Change focus up/down window stack |
| Super + shift + j/k | Swap up/down window stack |
| Super + h/l | Move the centre split left/right |
| Super + Space | Change focus to master |
| Super + shift + Space | Promote current window to master |
| Super + ,/. | Change focus to next/prev monitor |
| Super + shift + ,/. | Move window to next/prev monitor |
| Super + f | Toggle monocle mode |
