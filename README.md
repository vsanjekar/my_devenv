vinay_devenv
============

Use the setup script.

mkdir ~/github
Copy the repo to ~/github
Install rbenv

* Bash
------
* **OSX:**

ln -s ~/github/vinay_devenv/.bash_profile ~/.bash_profile

ln -s ~/github/vinay_devenv/.alias ~/.alias

* **Linux:**

ln -s ~/github/vinay_devenv/.bashrc ~/.bashrc

ln -s ~/github/vinay_devenv/.alias ~/.alias

* VIM
-----

* Install silversearcher

https://github.com/ggreer/the_silver_searcher/downloads

Get this version: the-silver-searcher_0.7.3-3_amd64.deb The Silver Searcher 0.7.3 x86-64 for Ubuntu 12.04.

sudo dpkg -i the-silver-searcher_0.7.3-3_amd64.deb

* Install Vundle

git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

* Use the vimrc with awesome plugins

ln -s ~/github/vinay_devenv/.vimrc ~/.vimrc

vim
:PluginInstall


* GIT
-----
ln -s ~/github/vinay_devenv/.gitconfig ~/.gitconfig
