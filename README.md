# dotfiles
A collection of some of my dotfiles

[.zshrc](.zshrc): A simple ZSH config, depends on `zsh-autosuggestions` and `zsh-syntax-highlighting`. Only tested on Void Linux in Xfce Terminal with the Monospace Regular font, needs modifications for use on Ubuntu.

[flameshot-fullscreen-capture.sh](flameshot-fullscreen-capture.sh) and [flameshot-region-capture.sh](flameshot-region-capture.sh): Hacky workaround for not having the Flameshot daemon run after a screenshot has been taken and copied to the clipboard. Depends on `bash`, `flameshot` and `xclip`. Probably doesn't work on Wayland.