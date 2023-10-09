# Installation instructions

Also several ways to install, but I think it matters less with `tmux` as it is not changing as quickly. 

Here is the link to the installation instructions

https://github.com/tmux/tmux/wiki/Installing#appimage-package


I think I just went for the `sudo apt update && sudo apt get tmux` option. I don't 100% remember.


# Plugins / Config

I think just the `tmux.conf` file in `.config/tmux` is enough to set up tmux. 

Note: using `tmux-continuum` autosaves the sessions every 5 minutes or so, and will auto reload the last saved state on resuming tmux. This is particularly useful for my WSL2 ubuntu that I shutdown tomake backups of.

