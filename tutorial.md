git教程

https://blog.csdn.net/m0_48651355/article/details/120646834?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-120646834-blog-88870257.pc_relevant_multi_platform_whitelistv4&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-120646834-blog-88870257.pc_relevant_multi_platform_whitelistv4&utm_relevant_index=1



```bash
git init //把这个目录变成Git可以管理的仓库
git add README.md //文件添加到仓库
git add . //不但可以跟单一文件，还可以跟通配符，更可以跟目录。一个点就把当前目录下所有未追踪的文件全部add了 
git commit -m "first commit" //把文件提交到仓库
git remote add origin git@github.com:lzhdelife/Weekly_Report.git //关联远程仓库
git push -u origin master //把本地库的所有内容推送到远程库上
```



更改后上传GitHub

```bash
git status -s  // 查状态
git add . //不但可以跟单一文件，还可以跟通配符，更可以跟目录。一个点就把当前目录下所有未追踪的文件全部add了 
git commit -m "first commit" //把文件提交到仓库
git remote add origin git@github.com:lzhdelife/Weekly_Report.git //关联远程仓库
git push -u origin master //把本地库的所有内容推送到远程库上
```



做出一些更改（测试）
