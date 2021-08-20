
# python虚拟环境搭建

安装

```
pip install virtualenvwrapper
```

环境变量：
添加以下内容到`~/.bash_profile`，然后执行`source ~/.bash_profile`

```
export WORKON_HOME=$HOME/.virtualenvs
export PROJECT_HOME=$HOME/Devel
source /usr/local/bin/virtualenvwrapper.sh
```

如果找不到`virtualenvwrapper.sh`，使用命令`sudo find / -name virtualenvwrapper.sh`查找文件位置

## 命令

```
workon: 列出所有虚拟环境
mkvirtualenv spider_1: 创建虚拟环境
workon spider_1: 激活并进入虚拟环境
deactivate spider_1: 退出虚拟环境
rmvirtualenv spider_1: 删除虚拟环境
```
