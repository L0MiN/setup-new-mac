# Setup a new Mac
This is a guide on how to setup a new Mac. It is mainly for myself, but feel free to use it as well.

## Configurations and Installations

### ssh
1. generate id_rsa and id_rsa.pub using ```-t ed25519 -C "<your email>"``` as described here: https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
2. add the public key to your github account as described here: https://docs.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account
3. add the private key to your ssh agent as described here: https://docs.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account
4. add your passphrase to the keychain as described here: https://docs.github.com/en/github/authenticating-to-github/working-with-ssh-key-passphrases#macos or use ```ssh-add -K ~/.ssh/id_ed25519``` to add it to the keychain

### zsh Prezto
1. Install zshprezto as described here: 
https://github.com/sorin-ionescu/prezto

2. After following all of the steps mentioned in the prezto Github Repository, replace the duplicate items from this repositories prezto folder with the ones in ~ 

### homebrew
1. Install homebrew as described here: 
https://docs.brew.sh/Installation
2. Run ```brew update && brew upgrade```

### git
1. Replace the .gitconfig in ~ with the one from this repository and replace the ermail address with your corporate email
2. add .gitconfig_private to ~

### nvm 
1. Install mvn according to the steps mentioned here: https://www.digitalocean.com/community/tutorials/install-maven-mac-os
2. run ```nvm install lts/hydrogen``` to get the latest version of node 18 (node 18 is no longer lts, but you can still use the lts codename to install it)
3. run  ```nvm install lts/iron``` to get the latest version of node 20
4. run ```nvm alias default lts/iron``` to set node 20 as global default
5. run ```nvm install 21``` to get the latest version of node (january 2024)

### Java JDK
1. Install the latest Java SDKs using brew

## Important (at least for me) Applications
Install all of the following applications: 

- iTerm2
- Aerial Companion
- AltTab
- Bitwarden
- Chrome
- Discord
- Disk Graph
- Docker
- Figma
- IntelliJ IDEA
- iStat Menus
- Magnet
- OBS
- Pixelmator Pro
- Raycast
- Visual Studio Code


