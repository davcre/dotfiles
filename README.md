# Dotfiles

## Nvim
- Install vim-plug 
```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
- Add init.nvim to .config/nvim
- Run :PlugInstall inside nvim to install the plugins
- Run :PlugUpdate inside nvim to update plugins

## Tmux
- Install Tmux Plugin Manager (TPM)
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
- Add .tmux.conf to your home directory
- Reload Tmux with ```prefix + r```
- Install plugins with ```prefix + I```

## Zsh
- Install zsh
- Install oh-my-zsh
- Clone external plugins to ```~/.oh-my-zsh/custom/plugins```
  - zsh-autocomplete
  - zsh-autosuggestions
  - zsh-syntax-highlighting
  - zsh-history-substring-search
  - autoswitch-virtualenv
- Install thefuck, command-not-found and fzf packages
- Add .zshrc to your home directory
- To reload zsh run ```omz reload```
- To make zsh as a default shell run ```sudo chsh -s $(which zsh) $(whoami)```

## Git
- Install git
- Add .gitconfig to home directory

## Alacritty
- Install Alacritty terminal
- Add alacritty.toml to .config/alacritty
- Add nord.toml to .config/alacritty/themes
