# How to use?

## Dump gnome shell extension settings:

```bash
dconf dump /org/gnome/shell/extensions/ > ~/.config/gnome-dump/gnome-dump.txt
```

## Load gnome shell extension settings:

```bash
dconf load /org/gnome/shell/extensions/ < ~/.config/gnome-dump/gnome-dump.txt
```
