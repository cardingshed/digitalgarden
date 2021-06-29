---
title: "shell"
weight: 3
subtitle: ""
excerpt: "oh my zsh, iterm 2"
---

## initial system tweaks
Change screenshot folder (default is to clutter the desktop)
```
defaults write com.apple.screencapture location 
<<target folder>>
```
Permanently unhide library folder
```
chflags nohidden ~/Library/
```
Restart processes after changes
```
killall SystemUIServer
```

## configure terminal
Install feature-rich terminal **iterm2** from [here](https://iterm2.com)

zsh is now the default shell in macOS **oh my zsh** [website](https://ohmyz.sh) can be installed with
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## homebrew
Need this.  Details on the homebrew [website](https://brew.sh)
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Keep up to date with
```
brew update && brew upgrade
```

## git
Can use homebrew to install latest version of **git**. Apple's version of **git** is included in **command line tools** (download when prompted, don't need the full 15GB of XCode). 
```
brew install git
git --version
```
If the version still mentions Apple, then run
```
export PATH=/usr/local/bin:$PATH
git --version
```
Can then configure with
```
git config --global user.name <<my github username>>
git config --global user.email <<my email>>
```


