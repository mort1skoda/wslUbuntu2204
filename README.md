## WSL Ubuntu 20.04
### dotfiles
#### /home/m/ 

* .bashrc  .bash_aliases
* .vimrc   .vimfm
* .tmux.config  makefiles
* .gdb.config
* C small multifile demos
* ~\demoC including gdb
* ~\demoHtml

<pre>
Use cmd or powershell
wsl --list --online
wsl --install -d Ubuntu-22.04

open Ubuntu-22.04
sudo apt update -y
sudo apt upgrade -y
sudo apt autoremove

sudo apt install git -y
sudo apt install gh -y
gh auth login
    GitHub.com
    HTTPS
    y
    Login with a web browser
    copy your one-time code: XXXX-XXXX
 </pre>

* and go to https://github.com/login/device

<pre>
git config --global user.name "Your Name"
git config --global user.email "yourmail@yourdomain.com"
git config list
cat .gitconfig
git pull https://github.com/mort1skoda/wslUbuntu2204.git

</pre>

---
* git pull https://github.com/mort1skoda/wslUbuntu2204.git
* git remote -v
---
* ./gitPush.sh   /   alias gp
* cat gitPush.sh to see "how it's done"
* alias c='cat '    c gitPush.sh
* push all the dotfiles in /home/user/
* including the folders:
* .config .landscape .local .vifm .vim
---
* other user data /dat
* Like: 
* devC devHtml devLfs
* they have their own,
* repositories with gitPush.sh
* inside each of their folders
---



