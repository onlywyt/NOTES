# Mac 安装 pip
在安装Python的目录下运行如下代码：
~~~ 
 curl https://bootstrap.pypa.io/get-pip.py | python3
~~~ 
## pip是什么
pip 是 Python 包管理工具，该工具提供了对Python 包的查找、下载、安装、卸载的功能。
可以通过 ` pip3 --version ` 查看是否安装。pip3 --version是Python3的命令，pip --version 是Python2的命令
## pip常用命令
卸载包
`pip uninstall SomePackage`

搜索包
`pip search SomePackage`

显示安装包信息
`pip show `

查看指定包的详细信息
`pip show -f SomePackage

`列出已安装的包
`pip list`
查看可升级的包
`pip list -o`
## mac 系统升级pip
- python2 
`pip install --upgrade pip `
- python3
`pip3 install --upgrade pip ` 