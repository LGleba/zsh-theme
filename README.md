# zsh-theme


## 1. Install brew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
```
brew -v
```


## 2. Install zsh
```
zsh --version
```

## 3. Install Oh My Zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
```
cat ~/.zshrc
```

## 4. Install Powerlevel10k
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

Set in `~/.zshrc`
```
ZSH_THEME="powerlevel10k/powerlevel10k"
```

Reload iTerm2

Answers: 
- y - font
- y - diamond
- y - lock
- y - Debian logo
- y - icons
- 3 - rainbow
- 1 - Unicode
- 2 - curent time
- 1 - angled
- 1 - sharp
- 1 - flat
- 2 - two lines
- 2 - dotted
- 2 - left
- 4 - darkest
- 2 - sparse
- 1 - few icons
- 1 - concise
- n - disable transient prompt
- 1 - verbose
- y - changes

## 5. Install zsh-autosuggestions
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
Add in `~/.zshrc`
```
plugins=( 
    # other plugins...
    zsh-autosuggestions
)
```


## 6. Install zsh-completions
```
git clone https://github.com/zsh-users/zsh-completions ${ZSH_CUSTOM:-${ZSH:-~/.oh-my-zsh}/custom}/plugins/zsh-completions
```
Add in `~/.zshrc`
```
plugins=( 
    # other plugins...
    zsh-completions
)
```

## 7. Install zsh-syntax-highlighting
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
Add in `~/.zshrc`
```
plugins=( 
    # other plugins...
    zsh-syntax-highlighting
)
```



