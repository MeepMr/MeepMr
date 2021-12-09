- [ ] Install X-Code CL Tools
```
xcode-select --install
```

- [ ] Install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- [ ] Install ITerm2
```
brew install iterm2
```

- [ ] Install OhMyZsh
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

- [ ] Install Powerlevel10k
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

- [ ] Install ZshSyntaxHighliting
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

- [ ] Install ls
```
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/zpm-zsh/ls.git
```

- [ ] Install ZshAutoSuggestions
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

- [ ] Copy .zshrc into ~
- [ ] Copy .p10k.zsh into ~
