![](https://files.jb51.net/file_images/article/201409/git_big_jb51.jpg)
如果在github上创建了库
1,clone到本地
git clone git@github.com:changye01/Git-tips.git


添加远程库
git remote add origin git@github.com:changye01/Git-tips.git

如果创建了readme.md
$ git pull origin master

{创建分枝
$ git checkout -b new
查看分支
git branch
切换分支
git checkout branchName
合并某分支到当前分支
git merge branchName
合并分枝到master
git checkout master 
git merge branchName
删除分之
git branch -d branchName
}

3 添加所有文件到本地库
git add --a
添加文件
git add fileName

4 提交更改到本地库

git commit -m "描述"

5 push 本地库到远程库

git push origin -u master //第一次
git push origin master
