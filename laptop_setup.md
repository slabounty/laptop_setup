# Laptop Setup

## Install Chrome

## For Mechanical Keyboard
* Capslock => Control
* Option => Command
* Command => Option

## Install Brew
See Instructions on brew.sh
```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

## Install Git
```brew install git```

## Install Xcode (full installation needed for MacVim)
Install from App Store

## Install Macvim
```brew install macvim```

## Install Janus
```curl -L https://bit.ly/janus-bootstrap | bash```

## Install dotjanus
```git clone https://github.com/slabounty/dotjanus```

## Install zsh
```brew install zsh zsh-completions

## Install dotfiles
```
git clone https://github.com/slabounty/dotfiles
./dotlink
```

## Install rbenv
```
brew install rbenv
rbenv init # Need to add output to .zshrc?
rbenv install -l # List all ruby versions available
rbenv install 2.3.1
rbenv global 2.3.1 # Make this the default
```

## Install Silver Searcher (ag)
```brew install the-silver-searcher```

## Install Fonts
```
brew tap caskroom/fonts
brew cask install font-inconsolata # Source code pro too?
```

## Install iterm2
```
https://www.iterm2.com/downloads.html
# Set zsh  Preferences/General/Command zsh --login
```


