*开始使用github*

## git安装配置
    1. 下载安装git

    2. 配置
    $ git config --global user.name ‘’
    $ git config --global user.email ''

    3.建立一个本地Git代码库
    到指定目录 cd （可以直接从文件夹拖动）
    $ git init 在当前目录新建一个Git代码库（.git 目录）

    工作区 ==>> 缓冲区
    添加指定文件到暂存区
    $ git add [file1] [file2] ...
    添加指定目录到暂存区，包括子目录
    $ git add [dir]
    添加当前目录的所有文件到暂存区
    $ git add .
    添加每个变化前，都会要求确认
    查看状态
    $ git status
    提交
    $ git commit -m '提交说明'
    查看提交版本
    $ git log
    版本恢复
    $ git reset --hard '版本号'

    https://www.bilibili.com/video/BV1CJ411y7sa/?p=2

    操作github仓库
    $ ssh -keygen -t rsa -C "youremail@example.com"
    到文件id_rsa.pub，复制里面的 key。
    登录github账号，Account Settings >> SSH keys >> Add new

    在github创建hellogit仓库（创建完成会有说明，可以在浏览器内操作）
    git remote add origin https://github.com/ldc311/hellogit.git
    git push origin master -f
    
## vscode
    右键菜单中增加Open in Default Browsers，在插件中搜索open in，安装
## markdown
 https://zhuanlan.zhihu.com/p/56943330
