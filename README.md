# dotfiles

Personal `~/.config` files for an Arch Linux + Hyprland setup.

## Contents

| Path | What |
|------|------|
| `hypr/` | Hyprland compositor + hyprlock config |
| `waybar/` | Status bar |
| `wofi/` | Application launcher (Super+Space) |
| `dunst/` | Notification daemon |
| `ghostty/` | Terminal emulator |
| `btop/`, `htop/` | System monitors |
| `zed/` | Zed editor settings + themes |
| `gtk-3.0/`, `gtk-4.0/` | GTK theming |
| `scripts/` | Personal helper scripts |

## Restore on a fresh install

```sh
git clone https://github.com/<user>/dotfiles ~/.config-restore
# copy what you want into ~/.config, e.g.:
cp -r ~/.config-restore/hypr ~/.config/
```

Or, to track `~/.config` directly as the repo:

```sh
cd ~/.config
git init
git remote add origin https://github.com/<user>/dotfiles
git fetch origin
git checkout -f main
```
