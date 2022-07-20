# Wacom Scripts
This repo contains various simple scripts that make it easier to work with Wacom devices on Linux!
Feel free to star the repo if it helped you out.


# Features
Some basic features include:
* Mapping the tablet's surface area to a specific monitor
  * Matching aspect ratio to monitor's aspect ratio


# Dependencies
Please ensure all of the following programs are installed before running the script:
* bc
* gawk
* xorg-xrandr
* xf86-input-wacom
* fzf [Optional]
  * Used for selecting monitor

## Arch Linux
```bash
$ sudo pacman -S bc gawk xf86-input-wacom fzf
```

# Running
Just download, chmod, and execute!
```bash
$ curl https://raw.githubusercontent.com/Shinji322/wacom-scripts/main/wacom -o $HOME/.local/bin/wacom
$ chmod u+x $HOME/.local/bin/wacom
$ wacom # tadah!
```
