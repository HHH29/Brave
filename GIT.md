# STH for Git
## 1、git提交命令
初始化仓库：git init  
关联远端仓库：git remote add origin 仓库地址  
查看当前状态：git status  
添加所有文件：git add  
提交代码：git commit -m "提交说明"，-m表示message  
自动把已经被git跟踪过的文件添加到暂存区：git commit -am  
修改上一次提交说明：git commit --amend -m "新的提交说明"  
只提交指定文件:git commit 文件名 -m "提交说明"
推送代码到远端仓库: git push origin 分支名  
## 2、分支操作  
查看分支: git branch -a 可查看本地和远端所有分支  
查看远程分支: git branch -r  
创建分支: git branch 分支名/git checkout -b 分支名 checkout 会自动切换到该分支下  
切换分支: git switch 分支名/git checkout 分支名  
创建并切换分支: git switch -c 分支名，旧写法:git checkout -b 分支名  
合并分支: 先切换到要合并到的目标分支，比如main: git switch main,然后合并分支dev: git merge dev 把dev分支上的修改合并到main 分支  
删除本地分支: git branch -d 分支名  
强制删除分支: git branch -D 分支名  
重命名当前分支: git branch -m 新分支名  
重命名指定分支: git branch -m 旧分支名 新分支名  
推送分支到远端: git push origin 分支名  
拉取远程分支: git fetch   
删除远程分支: git push origin --delete 分支名  


  
