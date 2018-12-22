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
                     -A                             提交所有变化
                     -u                             提交被修改(modified)和被删除(deleted)文件，不包括新文件(new)
                     .                              提交新文件(new)和被修改(modified)文件，不包括被删除(deleted)文件

      (2) git commit -m '[descript]'                添加到缓存区

                     -a                             跳过add，直接commit 添加到缓存区

     （3）git status                                 查看项目在上次commit后是否有修改当前（修改）的状态
                     -s                            （简化显示）

      (4) git diff                                  尚未缓存的改动(详细信息，相当于git status 的详细版)
                     --cached                       缓存的改动
                     HEAD                           所有的改动
                     --stat                         显示摘要
     （5）git rm [file]                             移除已经缓存的文件(没有缓存无法移除)
                  -f [file]                         强制移除文件
                  --cached [file]                   把文件从缓存区移除，但是仍希望保留在工作目录中（也就是只从跟踪清单中移除）
                  -r [folder]                       移除文件夹和文件夹下所有的子目录

     （6）git mv [file] [folder]                     把文件引动至某个文件夹下
                 [file] [newFileName]               给文件重命名







