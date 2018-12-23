**1.git是什么？**

- git是分布式版本控制器。

**2.常用git命令？**

- git init 将该目录变成git可以管理的仓库。
- git add start.md 将文件start添加到仓库
- git commit -m"XXX" 把文件提交到仓库
- git remote add origin ssh  关联一个远程库
- git push -u origin master 将本地内容推送到远程（第一次推送master分支的所有内容，之后git push origin master推送最新修改；）
- git status

**3.Github如何搭建自己的仓库？**
步骤：
- new repository
- repository name

***4.如何打开从githu中下载的vue？***
步骤：
- git ssh/ip
- npm install
- npm run dev

5.关于协同工作
- git checkout project-name  可以把刚刚改动的去掉（再执行git status，没有红色文件名出现，则说明没有修改。）
- git status 
- git pull 可以把对方更新的文件pull到本地

*切分支：*
- git checkout -b 分支名（分支名一般代表正在做的事情，比如add-animation）

*git merge 合并分支*

当前分支是master
git checkout master 
把分支add-animation合并进来：
git merge add-animation