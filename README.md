After Pulling dotfiles, run
```
git submodule update --init
```
to add submodules

### Kitty
To make usre kitty i run in fullscreen, go to the kitty .desktop file, most likely here:
```
/usr/share/applications/kitty.desktop
```
and change `Exec=kitty` to `Exec=kitty --start-as fullscreen`
