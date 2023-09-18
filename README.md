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
