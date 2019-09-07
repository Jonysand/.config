# Initialization commands in shell
>just for linux OS

## System tools upgrade and update
```
sudo apt upgrade
sudo apt update
```

## Useful tools
```
sudo apt install python python-dev python3-dev
sudo apt install cmake build-essential
sudo apt install ranger neofetch
```

## Editor installation
```
sudo apt install neovim
```
check the environment variables eg. path to python

## Vundle(vim plugins tools) installation
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

## Config firewall
allow OpenSSH
```
sudo ufw allow OpenSSH
sudo ufw enable
```

## Installing server software
### Apache2
```
sudo apt install apache2
sudo ufw allow in “Apache Full”
```
### MySQL
```
sudo apt install mysql-server
sudo mysql_secure_installation
```

## ZSH (a usefull terminal)
Install zsh/oh my zsh
```
sudo apt install zsh
sudo sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
Download config files
```
sudo git clone https://github.com/Jonysand/.config.git
sudo cp -f .config/.zshrc ~/
```

