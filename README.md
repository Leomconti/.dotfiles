# .dotfiles

## My personal configuration files that I have on my setup

-   Mostly a personal backup, and version control for my dotfiles, also it's a way so I can have everything in one place and just use symbolical links to the correct places.

-   Not all of them are in the correct places, for example keyboards, you'll find it's a separated folder, which has my qmk files for my daily use corne split keyboard.

-   Configuration files for iterm, zsh, nvim... can be found here too.

# How to add new files here:

-   1. Move to the ./dotfiles

```sh
mv ~/.zshrc ~/.dotfiles/
```

-   2. Create symbolic links to the original config file locations

```sh
ln -sf ~/.dotfiles/.zshrc ~/.zshrc
```

Obs: To find the dotfiles you have to run

-   To get the files inside dotfiles

```sh
ls -al ~/.dotfiles
```

-   To get the files inside the home directory

```sh
ls -al ~
```
