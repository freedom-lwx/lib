git init
git clone username@host:/path/to/repository
git clone /path/to/repository



git add <filename>
git add *

git commit -m "代码提交信息"





git push origin master 推送到远程仓库origin的master分支
git remote add origin <server> 建立一个名为origin的远程仓库


git checkout -b fetch 创建一个叫做fetch的分支
git checkout master 切换到master分支

git branch -d fetch 将名为fetch的分支删除
git push origin branch 将名为branch的分支推送至名为origin的远端仓库



更新与合并
git pull <remote> <branch>从远端更新我的本地仓至最新改动,相当于在我的工作目录中获取fetch并合并merge远端的改动
git merge <branch> 合并branch分支到我的当前分支

git add <filename> 当merge操作出错后,人肉处理冲突然后手动add
git diff <source_branch> <target_branch> 在改动之前可以看看两个分支之间的区别



替换本地改动
git checkout -- <filename> 如果做错事了就可以使用HEAD中的最新内容替换掉我的工作目录中的文件，当然已添加到缓存区的改动，以及新文件都不受影响
git fetch origin 
git reset --hard origin/master 如果想要丢弃本地的所有改动和提交，可以到服务器上获取最新的版本并将本地分支指向到它



ssh -T git@github.com 通过该命令查看ssh是否配置成功