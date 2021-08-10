
### 1. 什么是jupyter，有什么用
全名 jupyter notebook，是一个python编辑和运行的工具，集编辑和写作于一身

以代码块和单元格的形式运行，把文字和代码分区块存放，可以单独执行每个区块中的代码。
优势是可以方便查看中间变量运行结果，方便调试，找出bug

可以插入markdown的说明性文字，使代码可读性非常强，优于注释

可以分享成html/markdown/PDF等文件格式，可以支持发到网上，做成ppt。可以在云端运行。

除了python，还支持js和ruby

它的内核是ipython，是一个更高级的python解释器

jupyter notebook生成的文件格式为.ipynb

### 2. 怎么安装配置jupyter

```bash
pip install jupyter
```


### 3. 怎么使用jupyter

运行`jupyter notebook`，跳出浏览器，自动打开当前目录
```bash
jupyter notebook
```

右上角的New可以创建文件夹、文件(python/text/terminal)
点击顶部的文件名可以重命名

jupyter notebook python文件的内容划分为很多单元格

单元格有两种形式：代码，markdown文档
表示代码的单元格前有In[3]，数字表示当前文件的第多少次执行
表示markdown的单元格前是空白

单元格有两种状态：命令行模式(蓝色)和编辑模式(绿色)，命令行模式按回车进行编辑模式，编辑模式按esc回到命令行模式

命令行模式有以下命令：
m: 单元格切换到markdown模式
y: 单元格切换到代码模式
l: 如果单元格是代码模式，给代码标上行号
x: 剪切单元格
c: 复制单元格
v: 在下一行粘贴单元格
shift + v: 在上一行粘贴单元格
dd: 删除单元格
a: 在上方创建代码单元格，默认命令行模式
b: 在下方创建代码单元格，默认命令行模式
z: 恢复上个最删除或剪切的单元格

编辑模式下按以下命令运行单元格：
command + enter: 运行/渲染当前单元格，进入命令行模式
shift + enter: 运行/渲染当前单元格，同时跳到下一个单元格，如果下方没有单元格，新建一个单元格，新建单元格默认编辑模式

cell -> run all：从上到下，运行所有代码代码单元格
