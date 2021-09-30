1-新建项目 此时只有 master 分支
执行 git push -u origin main 把本地分支关联远程仓库 此时 本地 master 分支变成 main 分支
此时可以 git status 看下文件状态 如果还有未提交的文件 执行提交即可

2-本地新建分支 切换主分支 合并需要合并的分支 然后 git add git commit git push ---本地合并分支 推送远程服务器 main

3-本地新建分支 git add git commit git push origin （分支名称） ---效果是远程服务器 新增一个分支

4- 如果需要合并 远程的 main 和 dev 分支  
 1.本地合并 git merge dev 2.如果 dev 的文件都有 commit 过 那么直接就 git push main 远程分支 3.查看服务器是否有新的文件产生 4.删除远程分支 git push origin --delete XXX

5-git push origin --delete XXX 删除远程分支

6-git reset --hard HEAD^ 回到上一个版本

7-git push --set-upstream origin dev //dev 为创建分支的名字 1

8-
