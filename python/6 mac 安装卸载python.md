
## mac 安装python
brew install python
python3安装在`/usr/local/Cellar/python@3.9`
添加命令`/usr/local/bin/python3`，指向`/Cellar/python@3.9/3.9.6/bin/python3`


## mac 卸载python
rm -rf /Library/Frameworks/Python.framework
rm -rf /Applications/Python*
rm /usr/local/bin下指向python3的链接
删除python环境配置
vi ~/.bash_profile


## 安装包
pip3 install <package>
They will install into the site-package directory
  /usr/local/lib/python3.9/site-packages
