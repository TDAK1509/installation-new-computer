# New computer installations

## Core

- Install homebrew

## Terminal installations

### Iterm2

### Xcode

```
xcode-select --install
```

### Vim

```
vim ~/.vimrc
```

```
set number
syntax on
```

### Brews

```
brew install zsh
brew install fd
brew install bat
brew install fzf
brew install gh
brew install tree
brew install ripgrep
```

### oh-my-zsh

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### volta

```
curl https://get.volta.sh | bash
```

### ZSH Configuration

Theme

```
ZSH_THEME="amuse"
```

Others

```
# fzf
export FZF_DEFAULT_COMMAND="fd --type f --hidden"
export FZF_DEFAULT_OPTS='--no-height --color=bg+:#343d46,gutter:-1,pointer:#ff3c3c,info:#0dbc79,hl:#0dbc79,hl+:#23d18b'

export FZF_CTRL_T_COMMAND="$FZF_DEFAULT_COMMAND"
export FZF_CTRL_T_OPTS="--preview 'bat --color=always --line-range :50 {}'"

# Add custom scripts
export PATH="$HOME/Documents/Sites/installation-new-computer/bin:$PATH"
```

### zoxide

https://github.com/ajeetdsouza/zoxide
