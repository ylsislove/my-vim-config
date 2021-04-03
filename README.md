# my-vim-config
个人vim配置

## 使用方法
1. 克隆本仓库
```
git clone https://github.com/ylsislove/my-vim-config.git
```

2. 创建软链接
```
ln -s ~/my-vim-config/.vim ~/.vim
ln -s ~/my-vim-config/.vimrc ~/.vimrc
```

3. 下载vundle
```
cd .vim/
mkdir bundle
git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
```

4. 通过vundle安装插件
```
vim
:PluginInstall
```

## 参考
* [vim插件的安装(NERDTree)](https://www.jianshu.com/p/181c2b3ca7b5?utm_campaign=shakespeare)
