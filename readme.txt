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