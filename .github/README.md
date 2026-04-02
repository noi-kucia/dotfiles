# Dotfiles
These are my [Dotfiles](https://wiki.archlinux.org/title/Dotfiles) I use on everyday on my arch-based distros.

# Prerequisites
- [Oh my zsh](https://ohmyz.sh/) installed - `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
- git installed (obviously) - `sudo pacman -S git`

# How to install
  TODO: write a script to automatically install dotfiles + backup of existing ones
  something like `sh -c "$(curl -fsSL https://raw.githubusercontent.com/noi-kucia/dotfiles/main/script/install.sh"`

# How to update or add a dotfile
Add the file with `config add <file>` using an alias **config** defined in `.zshrc` file.

Commit changes with `config commit <file> -m <commit message>` and push it - `config push`.

> `config` here is just an alias to git command bound to this repo.
