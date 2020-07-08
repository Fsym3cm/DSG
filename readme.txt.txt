1.关联一个远程库，使用命令 git remote add origin git@https://github.com/Fsym3cm/DSG.git
2.关联后，使用命令git push -u origin master第一次推送master分支的所有内容
3.查看分支：git branch
4.创建分支：git branch <name>
5.切换分支：git checkout <name>或者git switch <name>
6.创建+切换分支：git checkout -b <name>或者git switch -c <name>
7.合并某分支到当前分支：git merge <name>
8.删除分支：git branch -d <name>
9.查看远程库信息，使用git remote -v；
10.本地新建的分支如果不推送到远程，对其他人就是不可见的；
11.从本地推送分支，使用git push origin branch-name，如果推送失败，先用git pull抓取远程的新提交；
12.在本地创建和远程分支对应的分支，使用git checkout -b branch-name origin/branch-name，本地和远程分支的名称最好一致；
13.建立本地分支和远程分支的关联，使用git branch --set-upstream branch-name origin/branch-name；
14.从远程抓取分支，使用git pull，如果有冲突，要先处理冲突。