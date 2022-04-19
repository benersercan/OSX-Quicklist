1- install xcode
xcode-select --install

2- install Homebrew
https://brew.sh/index_tr

3- install git with HomeBrew
brew install git

4- install iterm2
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
or : brew install iterm2
code ~/.zshrc   => open up config file with vscode ( cmd+shift+p and search 'shell commands')
# update iterm2 settings -> colors, keep directory open new shell, keyboard shortcuts
config Iterm2 :*  https://gist.github.com/kevin-smets/8568070  with yT video and last step:
# https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh

5- install node and nvm 
install node js on site 
brew install nvm 
mkdir ~/.nvm 
vim ~/.bash_profile 
export NVM_DIR=~/.nvm
source $(brew --prefix nvm)/nvm.sh
source ~/.bash_profile
nvm ls-remote 
nvm ls
# https://tecadmin.net/install-nvm-macos-with-homebrew/

6- brew cask install alfred
# set CMD+space to launch alfred

Apps : 
1- Chrome 
2- VsCode 
3- Firefox 
4- Microsoft Edge 
5- Yandex
6- Opera 
7- Postman 
8- VLC Player
9- Spotify
10- Docker
11- Opera 
12- Microsoft Teams Outlook OneNote Excel etc.
13- Discord 
14- Open Vpn 


Browser Extention : 
1- OneTab
2- ACCES CONTROL ALLOW ORIGIN CORS
3- Datalayer checker 
4- Edit This Cookie 
5- Vue js devtools 
6- React devtools 
7- JSON Viewer 
8- Local Storage Manager

Homebrew/terminal/bash
OSX Settings - Dock/Finder
Web Browser - Extensions - AdBlock, Privacy Badger, OneTab, JSONViewer, Stylus, Vue Devtools, React Devtools
Node.js - nvm
Code Editor - VsCode
Code Editor Extension