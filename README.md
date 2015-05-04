##前言
每次重装系统或者变更开发环境，配置文件都需要重新搞一遍，非常麻烦。
所以建了这个项目来保存各种配置文件

###1. vim
vim的配置文件来源于 https://github.com/amix/vimrc Basic version
修改的地方如下：
- 显示行号

####1.1 使用方法
将`vimrc`文件复制到主目录中并改名为`.vimrc`
```bash
cp vimrc ~/.vimrc
```

###2. zsh
zsh的配置文件来自https://github.com/robbyrussell/oh-my-zsh
修改的地方如下：
- 修改默认主题为`bira`
####2.1 使用方法
1. 将oh-my-zsh文件夹复制到主目录中并改名为.oh-my-zsh
2. 将.oh-my-zsh文件夹中的`zshrc`复制到主目录中并改名为`.zshrc`

```bash
cp oh-my-zsh ~/.oh-my-zsh -rv
cp ~/.oh-my-zsh/zshrc ~/.zshrc -v
```

