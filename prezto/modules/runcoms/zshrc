# Source Prezto.
if [[ -s "${ZDOTDIR:-$HOME}/.zprezto/init.zsh" ]]; then
  source "${ZDOTDIR:-$HOME}/.zprezto/init.zsh"
fi

unsetopt IGNORE_EOF

#aliases
alias ll="ls -la"
alias ..="cd .."
alias reload="source ~/.zshrc"
alias gcb="git checkout -b"



#Application aliases
alias code="open -a Visual\ Studio\ Code"



#change appereance
export CLICOLOR=1
export LSCOLORS=gxBxhxDxfxhxhxhxhxcxcx



#dev settings

export NPM_PACKAGES="$HOME/.npm-packages"
export PATH="/opt/homebrew/bin:$PATH"


export NVM_DIR="$HOME/.nvm"
[ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && . "/opt/homebrew/opt/nvm/nvm.sh"  # This loads nvm
[ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && . "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion


function log() {
echo $1
osascript -e "display notification \"$1\" with title \"$2\""
}



function startcom() {
log "Start Microsoft Outlook" "Communication"
open -a "Microsoft Outlook"
log "Start Microsoft Teams" "Communication"
open -a "Microsoft Teams"
log "Start Firefox Developer Edition" "Communication"
open -a "Firefox Developer Edition"
}



function startdev() {
log "Start IntelliJ IDEA" "Development"
open -a "IntelliJ IDEA"
}



function work() {
startcom
startdev
}
export PATH="/Library/Java/JavaVirtualMachines/openjdk.jdk/Contents/Home/bin:$PATH"


# Load Angular CLI autocompletion.
source <(ng completion script)
