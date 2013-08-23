## About This Repository
This is My Mac Config.  
  
This only have

* [shingo-nakanishi/git-config](https://github.com/shingo-nakanishi/git-config)
* [shingo-nakanishi/vim-config](https://github.com/shingo-nakanishi/vim-config)
* [shingo-nakanishi/zsh-config](https://github.com/shingo-nakanishi/zsh-config)

as submodule

## Install

```
$ cd ~
$ git clone git@github.com:shingo-nakanishi/my-config.git
$ cd my-config
$ git submodule init
$ git submodule update
$ git submodule foreach 'git checkout master'
```

## Set Up git-config

Read [shingo-nakanishi/git-config](https://github.com/shingo-nakanishi/git-config) README.md of
* [Make symbolic link](https://github.com/shingo-nakanishi/git-config#make-symbolic-link)
* [Edit ~/.gitconfig](https://github.com/shingo-nakanishi/git-config#edit-gitconfig)

## Set Up vim-config

Read [shingo-nakanishi/vim-config](https://github.com/shingo-nakanishi/vim-config) README.md of
* [Edit ~/.vimrc](https://github.com/shingo-nakanishi/vim-config#edit-vimrc)

## Set UP zsh-config
Read [shingo-nakanishi/zsh-config](https://github.com/shingo-nakanishi/zsh-config) README.md of
* [Edit /etc/zshenv](https://github.com/shingo-nakanishi/zsh-config#edit-etczshenv)
* [Open New zsh](https://github.com/shingo-nakanishi/zsh-config#open-new-zsh)

## IF You are Me!!
* Install Xcode
* Install [olivierverdier/zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt)
* Install rbenv

And then
```
$ cd ~/my-config/zsh-config
$ git ch shingo-nakanishi
```
