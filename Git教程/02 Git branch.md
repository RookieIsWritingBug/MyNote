~~~markdown
# Git 中的分支

branch : 保证稳定版本的代码不会被破坏 , 不同的功能可以由不同的人操作

创建 feature1 分支 : git branch feature1

查看分支是否被创建 : git branch

按 q 退出预览

切换到 feature1 分支 : git checkout feature1

ll

touch a.txt

vim a.txt -> this is a.txt

git add a.txt

添加到仓库中 : git commit -m "add a.txt"

git branch feature2

git checkout feature2

cat a.txt

创建 feature3 分支并且换到 feature3 分支 : git checkout -b feature3
-b 就是 -branch

删除 feature2 分支 : git branch -d feature2

将 feature3 中的内容合并到 master 中 : git merge feature3

将本地到操作提交到远程 : git push

将 feature1 分支提交到远程 : git push origin feature1

删除远端的 feature1 分支 : git push origin :feature1

将 feature1 分支提交到远端并重命名为 f1 : git push origin feature1:f1
~~~

![image-20211005213206021](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20211005213206021.png)

![image-20211005213239688](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20211005213239688.png)



##### 【笔记来源】[Everyone should understand Git #03 Git branch](https://youtu.be/cdBFxeSvD2Q)

