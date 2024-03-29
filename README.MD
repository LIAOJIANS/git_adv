1. **初始化仓库** ：

* `git init`：在当前目录下创建一个新的Git仓库。

1. **添加与提交文件** ：

* `git add <file>`：将指定文件或所有修改（通过 `git add .`）添加到暂存区。
* `git commit -m "<commit message>"`：将暂存区中的内容提交到本地仓库，并附带一条简短的提交信息。

1. **查看状态与差异** ：

* `git status`：显示工作目录和暂存区的状态，哪些文件被修改、未追踪等。
* `git diff`：比较工作目录中文件与暂存区的差异；加上 `--cached`参数可以查看暂存区与最近一次提交之间的差异。

1. **分支与合并** ：

* `git branch <branch-name>`：创建一个新的分支。
* `git checkout <branch-name>`：切换到指定的分支。
* `git merge <branch-name>`：将指定分支合并到当前分支。

1. **远程仓库操作** ：

* `git clone <repository-url>`：克隆一个远程仓库到本地。
* `git push <remote> <branch>`：将本地分支的更新推送到远程仓库。
* `git pull <remote> <branch>`：从远程仓库拉取更新并合并到本地分支。
* `git fetch`：从远程获取最新提交信息但不自动合并到当前分支。

1. **版本回滚与重置** ：

* `git reset --hard <commit_hash>`：回滚到某一次提交。
* `git revert <commit_hash>`：创建一个新的提交来撤销某次提交所做的更改。

1. **其他常用命令** ：

* `git log`：查看提交历史记录。
* `git diff <commit1> <commit2>`：比较两次提交之间的差异。
* `git stash`：暂存当前工作区的更改，以便稍后恢复。
* `git rm <file>`：从Git中删除文件。
* `git mv <old-file> <new-file>`：重命名文件。
