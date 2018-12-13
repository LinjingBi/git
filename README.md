#上传本地项目到github
```
$ mkdir demo
$ cd demo
$ touch README.md
$ git init //把这个目录变成Git可以管理的仓库
$ git add README.md //添加单一文件，将readme加入仓库
$ git add. // '.'表示把当前目录下所有未追踪的文件都添加了
$ git status //随时都可以用，用来查看当前工作区状态（等待提交的变更）
$ git commit -m 'first commit' //把文件提交到仓库
$ git remote add origin git@github.com:username/repositoryname.git //关联远程仓库
$ git push -u origin master
```
#下载操作
```
$ git pull origin master //把远程仓库更改拉到本地
$ git clone https://github.com/username/repositoryname.git //克隆远程仓库到本地
```
