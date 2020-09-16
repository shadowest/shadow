# shadow

利用 git 同步 github 指令

```python
    # 右键点击 Git Bash HERE
    genggai

    git init
    # 初始化文件夹
    git remote add origin git@github.com:shadowest/shadow.git
    # 增加我们对某个项目的管理


    git config --global core.autocrlf false 
    # 解决Git提交代码发生LF will be replaced by CRLF in 问题
    # 如果在add时出现问题则输入，否则不用输入
    /////

    git add .
    # 上传所有文件到仓库
    git add redme.txt
    # 上次readme.txt到仓库
    # 如果只是修改，则不用add

    git add -u
    # 将文件的修改、文件的删除，添加到暂存区。
    git add .
    # 将文件的修改，文件的新建，添加到暂存区。
    git add -A
    # 将文件的修改，文件的删除，文件的新建，添加到暂存区。

    git commit -m "这里写下你自己的记录本次提交内容的信息"
    # -m后面跟提示信息不仅是规则，同时也方便我们记录我们提交的过程
    # 将add上传到仓库的文件提交

    git commit –am "本次提交描述"
    # 该命令会将本地工作区中修改后，还未使用git add . 命令添加到暂存区中的文件也一并提交上去。
    # 相当于git add -u 与git commit –m “本次提交描述”两句操作合并为一句进行使用

    git status命令
    # 查看工作区状态

    git pull git@github.com:shadowest/shadow.git
    # 在本地同步某一个仓库下的内容
    git push git@github.com:shadowest/shadow.git
    # 把已提交的代码推送到远程仓库上面去

```
