# Git简易手册

*   工作区与版本库

    ![工作区与版本库说明图](/img/git.jpg)

*   创建版本库

    初始化一个Git仓库，使用`git init`命令。  
    添加文件到Git仓库，分两步：
    + 第一步，使用命令`git add <file>`，注意，可反复多次使用，添加多个文件；
    + 第二步，使用命令`git commit`，完成。
    
*   版本管理

    + 要随时掌握工作区的状态，使用`git status`命令。
    + 如果git status告诉你有文件被修改过，用`git diff`可以查看修改内容。
    + HEAD指向的版本就是当前版本，因此，Git允许我们在版本的历史之间穿梭，使用命令`git reset --hard commit_id`。
    + 穿梭前，用`git log`可以查看提交历史，以便确定要回退到哪个版本。
    + 要重返未来，用`git reflog`查看命令历史，以便确定要回到未来的哪个版本。
    + 当你改乱了工作区某个文件的内容，想直接丢弃工作区的修改时，用命令`git checkout -- file`
    + 当你想撤销暂存区的修改时，使用命令`git reset HEAD file`
    + 命令`git rm`用于删除一个文件。
    
*   远程仓库

    + 关联一个远程库，使用命令`git remote add origin git@server-name:path/repo-name.git`
    + 关联后，使用命令`git push -u origin master`第一次推送master分支的所有内容
    + 使用命令`git push origin master`推送最新修改
    + 克隆远程仓库使用命令`git clone`
    
*   分支管理
*   标签管理
*  github使用
