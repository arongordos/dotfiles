# Dotfiles

1. Install Homebrew

```zsh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. Clone repository

```zsh
git clone git@github.com:arongordos/dotfiles.git ~/dotfiles
```

3. Create symlink

```zsh
ln -s ~/dotfiles/.zshrc ~/.zshrc
```

4. Run

```zsh
brew bundle --file ~/dotfiles/Brewfile
```