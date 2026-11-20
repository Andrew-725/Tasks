# GitHub
## 提交错了
点进仓库主页，点commits，找到错误的那条记录，点击后右上角会有一个...，点击后选择Revert commit进行反向修改
## 冲突
PR界面点击Resolve conflicts，手动修改，点击Mark as resolved，全部修改完成后点击Commit merge，回到PR界面点击合并
 # GitBash
 ## 版本回滚
 git reset回到指定版本，git log查看提交历史，git revert反向修改抵消上次改动
 ## 冲突
 git pull发现冲突，同样是手动删掉<<<<<< ======== >>>>>>>标记，然后选择保留版本并保存，保存的文件同样先暂存、提交本地，再推送到仓库
