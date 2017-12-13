mkdir learngit 
cd learngit
pwd
git init  # Git 初始化命令
用notepad++编写一个文件 readme.txt

################################################################################
git add readme.txt   # 把文件添加到仓库
git commit -m "wrote a readme file"  # 把文件提交到仓库
git add file.txt file1.txt   # 可以同时提交几个文件

################################################################################

git status   # 查看当前仓库的状态 
会出现：modified:   readme.txt 
git diff readme.txt  # 告诉我们哪里改变了

################################################################################
git log  # 查看之前修改过几次记录
git log --pretty==oneline # 减少输出的东西，更明确




复制当前行： Ctrl+d
删除当前行： Ctrl+l
删除到行首： Ctrl+Shift+BackSpace
删除到行尾： Ctrl+Shift+Delete

折叠所有层次： Alt+0
展开所有层次： Alt+shift+0
折叠当前层次： Ctrl+Alt+f
展开当前层次： Ctrl+Alt+Shift+f

git is a version control system
git is free software
git is a distributed version control system
git is free software
