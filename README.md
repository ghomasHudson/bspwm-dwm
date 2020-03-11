# bspwm-dwm
Things to make bwpsm behave like dwm. Based heavily on the work of [ortango](https://gist.github.com/ortango/398e8404b031e2990597575f0560618f).

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
| Super + Space | Promote selected window to master |
| Super + f | Toggle monocle mode |
