# WIP example Hyprtheme theme

Test repo for Hyprtheme.

# TODO

## Dependencies

Dependencies are added to the `theme.toml` as Repology links and get installed via native package managers.

! What about things like `hyprland-git` which are not available in Repology.

## Assets

Assets are added to the `assets/` directory and get copied on installation to `~/.config/hyprtheme/assets/<theme-name>/`.

A user can invoke a command to clean up the directory from unused assets. However, they wont get uninstalled automatically, as he might want to use some of the wallpapers later on, for example. (dumb idea?)
