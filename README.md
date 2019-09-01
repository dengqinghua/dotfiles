Dotfiles
========

该部分为邓擎铧的配置文件汇总, 包括下面内容:

* vim
* tmux
* vimperatorrc

--------------------------------------------------------------------------------

vim
---
使用邓擎铧的配置vim配置, 需要执行下面的命令

1. 拷贝vim插件安装工具

        git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

2. 拷贝vimrc, 安装插件

        git clone https://github.com/dengqinghua/dotfiles.git ~/Downloads/dotfiles
        cp ~/Downloads/dotfiles/vim/vimrc ~/.vimrc
        vim +PluginInstall +qall

### ideavimrc
如果您使用IDE: [idea](https://www.jetbrains.com/idea/), 并在其中使用ideavim插件, 建议您配置ideavimrc

    git clone https://github.com/dengqinghua/dotfiles.git ~/Downloads/dotfiles
    cp ~/Downloads/dotfiles/vim/ideavimrc ~/.ideavimrc

tmux
----
我们使用tmux在服务器端进行分屏, 创建新的session等

```
git clone https://github.com/dengqinghua/dotfiles.git ~/Downloads/dotfiles
cp ~/Downloads/dotfiles/tmux.conf ~/.tmux.conf
```

vimperatorrc
-------------
Firefox的vim插件

```
git clone https://github.com/dengqinghua/dotfiles.git ~/Downloads/dotfiles
cp ~/Downloads/dotfiles/vimperatorrc ~/.vimperatorrc
```

termux
------
> Termux is an Android terminal emulator and Linux environment app

App 的安装和初始化配置见

- [官网](https://termux.com)
- [Wiki](https://wiki.termux.com/wiki/Main_Page)
- [推荐的中文入门文档](https://www.sqlsec.com/2018/05/termux.html)

### 安装App后的命令
```
pkg install vim curl wget git unzip unrar openssh hydra nmap python tmux golang rust
apt install -yqq nodejs ruby
npm install http-server -g
```


创建微信目录的下载文档的软链

```
ln -s /data/data/com.termux/files/home/storage/shared/tencent/MicroMsg/Download wx
```

### properties
配置一些快捷键

```
git clone https://github.com/dengqinghua/dotfiles.git ~/Downloads/dotfiles
cp ~/Downloads/dotfiles/termux.properties ~/.termux/
```

配置完后的效果:
![termux_image](https://raw.githubusercontent.com/dengqinghua/roses/master/assets/images/termux_properties_example.png)
