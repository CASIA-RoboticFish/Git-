# Git-Tips

这是关于Git的使用小贴士~~~~

很好的一个Git教程：https://www.liaoxuefeng.com/wiki/896043488029600

1、查看当前状态

git status 

2、将修改的文件存入暂存区

git add [文件名]

3、将暂存区的修改提交到本地的版本库

git commit -m "提交说明"  // 这里的-m参数表示后面跟了一个提交说明

4、删除一些不需要存入暂存区的文件（当你不小心add了一些你不需要的文件时，就可以使用这个函数）

git rm --cached [文件名]

5、将本地库与远程库建立连接

git remote add origin git@github.com:用户名/远程仓库名.git

git remote -v // 查看链接是否建立成功

6、上传本地版本库中的代码至远程版本库

git push origin [分支名]

7、下载远程版本库中的代码至本地版本库

git pull origin [分支名]

8、查看都有哪些分支

git branch

9、切换分支

git checkout [分支名]

10、新建分支

git checkout -b [新分支名]

git checkout -b [新分支名] origin/[新分支名]   // 创建新分支的同时，和远程分支建立连接

