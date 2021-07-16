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

# git checkout -b dev  创建并切换到dev分支
# git merge <name> 合并分支
# git stash 存储当前工作区
# git stash list 查看存储区的清单
# git apply [index] 恢复指定的stash      git stash drop 清空stash
# git stash pop 前两步的合体
