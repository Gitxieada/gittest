1.命令 :git init 
新建一个testgit版本库。
当前testgit目录下会多了一个.git的目录，这个目录是Git来跟踪管理版本的。
2.命令 git add readme.txt添加到暂存区里面去
3.命令 git commit告诉Git，把文件提交到仓库。
git commit -m 'readme.txt提交'

git status来查看是否还有文件未提交

4. 改下readme.txt内容，使用git status来查看下结果，会显示readme.txt文件已被修改，但是未被提交的修改；
使用git diff readme.txt，查看readme.txt文件到底改了什么内容


33333333333333