# BSPWM Config

Contains all configuration files necessary to run my BSPWM configuration. This
includes:

- BSPWM (WM itself)
- eww (status bar)
- sxhkd (keybindings)

## Dependencies

- BSPWM
- eww
- sxhkd
- A couple scripts from my [dotfiles](https://github.com/toalaah/dotfiles.git)
  (most scripts are self-contained within this repo though).
- notify-send + dunst (**optional**)
- jq (for some scripts)

## Installation via Stow

Symlinks the configuration files to the correct path via [GNU
stow](https://www.gnu.org/software/stow/manual). Alternatively you can just
manually copy-paste.

```shell
stow -t $HOME/.config .
```
