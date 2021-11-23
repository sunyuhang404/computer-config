
brew install nvm

# 修改 `/.zshrc 中的配置
export NVM_DIR="$HOME/.nvm"
[ -s "/usr/local/opt/nvm/nvm.sh" ] && . "/usr/local/opt/nvm/nvm.sh"  # This loads nvm
[ -s "/usr/local/opt/nvm/etc/bash_completion.d/nvm" ] && . "/usr/local/opt/nvm/etc/bash_completion.d/nvm"

https://qizhanming.com/blog/2020/07/29/how-to-install-node-using-nvm-on-macos-with-brew