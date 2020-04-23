# Personal Configuration Files

Nothing to see here, just a place for me to backup some configs.

## Key Repeat

```bash
defaults write -g InitialKeyRepeat -int 10
defaults write -g KeyRepeat -int 2
```

## Move Focus to Next Window Shortcut

![screenshot](./move_window_focus.png)

## Disable Dock Resize

```bash
defaults write com.apple.dock size-immutable -bool true; killall Dock
```
