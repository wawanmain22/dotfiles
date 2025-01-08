````
# My Dotfiles

Personal configuration files for my development environment.

## What's Inside

- `.config/`: Configuration files for various applications
- `tmux/`: Tmux configuration
- `.gitconfig`: Git configuration
- `.p10k.zsh`: Powerlevel10k (ZSH theme) configuration
- `.wezterm.lua`: WezTerm terminal configuration
- `.zshrc`: ZSH shell configuration

## Prerequisites

Make sure you have these tools installed:
- Git
- Zsh
- Tmux
- WezTerm
- Powerlevel10k

## Installation

1. Clone this repository:
```bash
git clone https://github.com/YOUR_USERNAME/dotfiles.git ~/dotfiles
````

2. Create symbolic links:

```bash
# Config folder
ln -s ~/dotfiles/.config ~/.config

# Tmux
ln -s ~/dotfiles/tmux/.tmux.conf ~/.tmux.conf

# Git
ln -s ~/dotfiles/.gitconfig ~/.gitconfig

# ZSH
ln -s ~/dotfiles/.zshrc ~/.zshrc
ln -s ~/dotfiles/.p10k.zsh ~/.p10k.zsh

# WezTerm
ln -s ~/dotfiles/.wezterm.lua ~/.wezterm.lua
```

## Optional: Automatic Installation

You can also use the installation script (coming soon):

```bash
cd ~/dotfiles
./install.sh
```

## Updating

To update the configurations:

```bash
cd ~/dotfiles
git pull
```

## Notes

- Make sure to backup your existing configurations before installing these dotfiles
- Some configurations might need additional setup or dependencies
- Check each application's folder for specific instructions

## License

Feel free to use and modify these configurations as you like.
