# dotfiles

## Clone repo
Clone repo in the `home` directory
```sh
git clone https://github.com/gabrielmelo/dotfiles ~/.dotfiles 
```

## Create symlinks
Create symlinks in the `home` directory to the real files intro the repro.

**zshrc**
```sh
ln -s ~/.dotfiles/zsh/.zshrc ~/.zshrc
```

**gitconfig**
```sh
ln -s ~/.dotfiles/git/.gitconfig ~/.gitconfig
```

**fish**
```sh
ln -s ~/.dotfiles/fish/config.fish ~/.config/fish/config.fish
ln -s ~/.dotfiles/fish/fish_variables ~/.config/fish/fish_variables
ln -s ~/.dotfiles/fish/fish_plugins ~/.config/fish/fish_plugins
```

**fisher**
```sh
ln -s ~/.dotfiles/fish/fisher.fish ~/.config/fish/fisher.fish
```

**fisher update plugins**
```sh
fisher update
```

**starship**
```sh
ls ~/.config/starship.toml ~/.dotfiles/starship/starship.toml
```