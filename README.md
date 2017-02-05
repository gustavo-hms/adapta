# Adapta
Adapta is a script for bspwm implementing dynamic desktops (the on demand creation and destruction of virtual desktops), much like Gnome Shell does.

## Installation

*Note: you need the fish shell installed in your system in order to use this script.*

Place the script in ~/.config/bspwm. Then put this line in your `bspwmrc`:

```sh
~/.config/bspwm/adapta &
```

Finally, if your `bspwmrc` has a line configuring the number of desktops, change it to:

```sh
bspc monitor -d 1
```

Otherwise, just put the above line in your `bspwmrc`.
