### setting step

- Follow step
  - Assume the Ubuntu enviornment

- command setting_start.sh

```sh
# vundle setting
$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim 

# build.sh -> c++17 build
$ sudo cp ./build.sh /usr/bin/

# cscope setting
$ sudo cp ./mkcscope.sh /usr/bin/

# bash setting -> prompt & git setting
$ cat append_bash >> ~/.bashrc 

# git commit setting
$ cp ./git_commit.sh /usr/bin/

$ cat copy_vimrc ~/.vimrc
# Write ":PluginInstall" into vim

```  
