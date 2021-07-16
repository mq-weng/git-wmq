## 做git练习

# git reset 回退版本
1.可以直接写版本号
2.用 head^ 回到上一版

# git status 查看仓库状态
# git diff 显示工作区与缓存区的区别
git diff 文件名

# git log 查看历史提交记录

# git checkout -- 文件名 丢弃工作区的修改

# git branch dev   创建分支
# git checkout dev   切换分支 用git switch也行

# git checkout -b dev  创建并切换到dev分支  git switch -c dev也中
# git merge <name> 合并分支

# git stash 存储当前工作区 (当前分支不能提交，却需要切分支debug时用到)
# git stash list 查看存储区的清单
# git apply [index] 恢复指定的stash      git stash drop 清空stash
# git stash pop 前两步的合体
# git cherry-pick  43c4f4b..ac1b8ad   能复制一个特定的提交到当前分支
# git remote    git remote -v 查看远程的仓库
# 建立本地分支和远程分支的关联，使用git branch --set-upstream branch-name origin/branch-name
# 在本地创建和远程分支对应的分支，使用git checkout -b branch-name origin/branch-name，本地和远程分支的名称最好一致；