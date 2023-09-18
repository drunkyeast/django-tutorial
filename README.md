# django-tutorial

# github initializiton
echo "# django-tutorial" >> README.md     
git init    
git add README.md   
git commit -m "first commit"  
git branch -M main 

git remote add origin git@github.com:drunkyeast/django-tutorial.git


git push -u origin main


这个排版好恶心啊, 我明明有空格, 但是github上面的markdown不能显示.


# git 恢复成上一次commit的样子
git reset --hard HEAD  恢复到上一次commit的样子, 但是注意还有Untracked files是不受git 管理的
如果要删除Untracked files, 可以用git clean -f 或者git clean -f -d 后者还会删除目录
也就是这两个命令一起用才能真正地完全恢复成上一次commit的样子


# 入门文档第6章
NMSL, 绝对是文档没有讲清楚, 浪费劳资好多时间, 曹尼玛的. 要是有个大佬指点我一下, 直接2分钟就能搞定.
入门文档到此结束.
结束语: 寻找正确的学习方法!!! 边看django文档边写程序是错误的学习方法.
