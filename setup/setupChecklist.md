- [x] Install X-Code CL Tools
```
xcode-select --install
```

- [x] Install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- [x] Install ITerm2
```
brew install iterm2
```

- [x] Install OhMyZsh
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

- [x] Install Powerlevel10k
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

- [x] Install ZshSyntaxHighliting
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

- [x] Install ls
```
cd ~/.oh-my-zsh/custom/plugins
git clone https://github.com/zpm-zsh/ls.git
```

- [x] Install ZshAutoSuggestions
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

- [x] Copy .zshrc into ~
- [x] Copy .p10k.zsh into ~

- [x] Run install-script
```
sh ./install-programs.sh
```

- [x] Link node 16
```
brew link --overwrite node@16 --force
```

- [x] Install AppStore Apps
  - Grand Perspective
  - HotKey
  - iA Writer
  - MS Word
  - MS Excel
  - MS PowerPoint
  - MS OneNote
  - MS OneDrive
  - Signal
  - GoodNotes

- [x] Dokumente, Desktop ... auf iCloud speichern
- [x] Log in to Docker

```
docker login -u mrmeep
docker login ghcr.io -u meepmr
```

- [x] Add Templates To iA Writer
- [x] Log into Jetbrains Toolbox
  - Install IntelliJ
  - Install Fleet
  - Install DataGrip
  - Install WebStorm

- [x] Configure MOS.app
- [x] Configure Sound-Control
- [x] Import Citations into Zotero
