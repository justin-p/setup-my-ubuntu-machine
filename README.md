# setup-my-ubuntu-machine

Temp repo

## notes

### raw disk mapping
https://www.youtube.com/watch?v=D9TePODkYME  
### other
gnome tweaks  
apt install gnome-shell-extensions  
 
Theme: Flat-Remix-GTK-Blue-Dark  
Plugins: Dash to Pannel  
Icons: Papirus - Dark  


buildin terminal colors  
bash -c  "$(wget -qO- https://git.io/vQgMr)"   

https://vitux.com/how-to-change-login-lock-screen-background-in-ubuntu/  
Fix: #lockbackground  
then find orange color, replace with blue  


sudo apt-get install gir1.2-gtop-2.0 gir1.2-networkmanager-1.0  gir1.2-clutter-1.0  
https://extensions.gnome.org/extension/120/system-monitor/  

https://extensions.gnome.org/extension/15/alternatetab/  

https://i.lensdump.com/i/A6gfXK.png  

https://github.com/ahmetsulek/flat-terminal/blob/master/Flat.terminal  

apt install zsh  
oh-my-zsh  

FireCode Net Font mona Retina  
git clone --depth 1 https://github.com/ryanoasis/nerd-fonts  

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting  
git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions  
git clone https://github.com/zsh-users/zsh-completions $ZSH_CUSTOM/plugins/zsh-completions  
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf && ~/.fzf/install  
git clone https://github.com/romkatv/powerlevel10k  

https://github.com/athityakumar/colorls  
https://stackoverflow.com/questions/37720892/you-dont-have-write-permissions-for-the-var-lib-gems-2-3-0-directory  
https://coderwall.com/p/0o64yq/rbenv-issues-when-switching-to-zsh  
sudo apt-get update  
sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev python-software-properties libffi-dev libssl1.0-dev  

```
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(rbenv init -)"' >> ~/.zshrc
exec $SHELL

git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.zshrc
exec $SHELL

rbenv install 2.3.1
rbenv global 2.3.1
ruby -v
```  
alias ls="colorls --sd -A"  

apt install powerline  
vim .tmux.conf     
  source /usr/share/powerline/bindings/tmux/powerline.conf  
