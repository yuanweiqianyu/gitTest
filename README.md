# gitTest
git练习文件


参考： http://www.runoob.com/git/git-basic-operations.html

一、git基础
    1、创建与获取项目
    （1）、创建
        cd [Directory]
        git init

     (2)、获取
        git clone [url]


    2、添加、上传
     （1）git add
                     -A  提交所有变化
                     -u  提交被修改(modified)和被删除(deleted)文件，不包括新文件(new)
                     .   提交新文件(new)和被修改(modified)文件，不包括被删除(deleted)文件

      (2) git commit -m '[descript]'

          git commit -a 跳过add，直接commit 添加到缓存区

     （3）git status      查看项目当前（修改）的状态
                     -s  （简化显示）

      (4) git diff                  尚未缓存的改动
                     --cached       缓存的改动
                     HEAD           所有的改动
                     --stat         显示摘要
      （5）





