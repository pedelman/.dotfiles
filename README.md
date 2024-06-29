# dotfiles

This project is designed to be run using GNU Stow. You can also manage the symlinks yourself or
copy the files manually.

First, make sure you [install Homebrew](https://brew.sh/).

- Clone this project into your home directory
- Navigate into dotfiles repo `cd ~/.dotfiles`
- Install Homebrew dependencies `brew bundle`
- `stow git nvim tmux zsh` (or pick a subset to apply)

### Global gitignore

Make sure you use an absolute path for the global gitignore configuration.

```
git config --global core.excludesfile ~/.gitignore_global
```
