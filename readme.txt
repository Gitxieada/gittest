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

5. 版本回退：
增加一行内容为33333333333333。
查看下历史记录，使用命令 git log 。 git log命令显示从最近到最远的显示日志。
版本回退操作，我想把当前的版本回退到上一个版本，可以使用如下2种命令，第一种是：git reset  -–hard HEAD^ 那么如果要回退到上上个版本只需把HEAD^ 改成 HEAD^^ 以此类推。那如果要回退到前100个版本的话，使用上面的方法肯定不方便，我们可以使用下面的简便命令操作：git reset  -–hard HEAD~100 即可。
通过如下命令即可获取到版本号：git reflog  
由此可知，增加内容3333的版本号是 b597e3b.我们现在可以命令

git reset  -–hard  b597e3b来恢复了

6. 添加远程库 
把一个已有的本地仓库与gittest关联，然后，把本地仓库的内容推送到GitHub仓库。
(1)git remote add origin https://github.com/Gitxieada/gittest.git

(2)git push -u origin master
把本地库的内容推送到远程，使用 git push命令，实际上是把当前分支master推送到远程。

