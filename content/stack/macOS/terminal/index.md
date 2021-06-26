---
title: "shell"
weight: 2
subtitle: ""
excerpt: "oh my zsh, iterm 2"
date: 2021-01-01
---

## Initial System tweaks
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

## Configure terminal
Install feature-rich terminal iterm2 from [here](https://iterm2.com)

zsh is now the default shell in macOS, pick up oh my zsh [here](https://ohmyz.sh)



