1-新建项目 此时只有 master 分支
执行 git push -u origin main 把本地分支关联远程仓库 此时 本地 master 分支变成 main 分支
此时可以 git status 看下文件状态 如果还有未提交的文件 执行提交即可

2-本地新建分支 切换主分支 合并需要合并的分支 然后 git add git commit git push ---本地合并分支 推送远程服务器 main

3-本地新建分支 git add git commit git push origin （分支名称） ---效果是远程服务器 新增一个分支
