# dotfiles

## Clone repo
Clone repo in the `home` directory
```sh
git clone https://github.com/gabrielmelo/dotfiles ~/.dotfiles 
```

## Create symlinks
Create symlinks in the `home` directory to the real files intro the repro.

zshrc
```sh
ln -s ~/.dotfiles/zsh/.zshrc ~/.zshrc
```

gitconfig
```sh
ln -s ~/.dotfiles/git/.gitconfig ~/.gitconfig
```