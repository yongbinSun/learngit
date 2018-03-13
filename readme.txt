git init：初始化仓库
git add 文件名：添加或修改文件
git commit -m "备注信息"：提交更改
git status：查看修改记录
git diff：查看具体修改信息
git log：显示从最近到最远的提交日志
git log --pretty=oneline：显示简略的提交日志
git reset --hard HEAD^：返回上（^的数量）个版本
git reset --hard commit id(版本号)：跳转到指定版本
git reflog：记录每一次提交和commit id
git diff HEAD -- 文件名：查看工作区和版本库里面最新版本的区别
git checkout -- 文件名：用版本库里的版本替换工作区的版本
git reset HEAD 文件名：把暂存区的修改撤销掉，重新放回工作区
git rm 文件名：删除文件
要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
关联后，使用命令git push -u origin master第一次推送master分支的所有内容；
此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；
git clone git@github.com:yongbinSun/gitskills.git：克隆远程库到本地库
git checkout -b dev：创建并切换分支
git branch dev：创建分支
git branch：查看所有分支
git checkout dev：切换分支
git merge dev：合并指定分支到当前分支
git branch -d dev：删除指定分支
test