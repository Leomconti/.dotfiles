# How to add new files here:

- 1. Move to the ./dotfiles

```sh 
mv ~/.zshrc ~/.dotfiles/
```

- 2. Create symbolic links to the original config file locations   
```sh
ln -sf ~/.dotfiles/.zshrc ~/.zshrc
```

Obs: To find the dotfiles you have to run

- To get the files inside dotfiles
```sh
ls -al ~/.dotfiles
```

- To get the files inside the home directory  
```sh
ls -al ~
```
