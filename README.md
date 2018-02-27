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

### 拷贝vim插件安装工具

```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

### 拷贝vimrc文件
```
git clone https://github.com/dengqinghua/dotfiles.git ~/Downloads/dotfiles
cp ~/Downloads/dotfiles/vim/vimrc ~/.vimrc
```

### 安装vimrc中的插件
```
# 在终端输入vim
vim

# 在vim中执行
:PluginInstall
```

### ideavimrc
如果您使用IDE: [idea](https://www.jetbrains.com/idea/), 并在其中使用ideavim插件, 建议您配置ideavimrc

```
git clone https://github.com/dengqinghua/dotfiles.git ~/Downloads/dotfiles
cp ~/Downloads/dotfiles/vim/ideavimrc ~/.ideavimrc
```

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
