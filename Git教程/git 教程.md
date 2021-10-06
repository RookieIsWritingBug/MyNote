~~~markdown
分布式管理工具

~~~

~~~markdown
安装 Git
cent OS
yum -y install git
apt-get install git-all
~~~



~~~markdown
Git 的基本命令

远端仓库 : https://github.com/biezhi/git-tutorial.git

全局配置 : 
git config --global user.name "biezhi"
git config -- global user.email "biezhi.me@gmail.com"

查看配置 : cat ~/.gitconfig

创建本机仓库 : mkdir git-tutorial

初始化 : git init

查看文件 : ll

创建 README.md 文件 : touch READMD.md

查看当前仓库状态 : git status

git add README.md

git rm --cached README.md

git add -A

git commit -m "add README.md"

添加远端链接 : git remote add origin https://github.com/biezhi/git-tutorial.git

git remote -v

将本机文件提交到远端仓库 : git push origin master
git push -u origin master

origin 远端 master 分支

克隆远程仓库 : git clone https://github.com/biezhi/git-tutorial.git
git clone https://github.com/biezhi/git-tutorial.git git-demo

进入 git-demo 目录 : cd git-demo

查看目录 : ll

vim README.md

git status

git add README.md

git commit -m "modify README.md"

git push

cd git-tutorial

cat README.md

git pull

cat README.md
~~~

##### 【笔记来源】[Everyone should understand Git #02 Git basic operation](https://youtu.be/OVLR9qRc9ak)

