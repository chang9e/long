今天学习了**git工作原理**，就是add和commit的工作过程。

首先先明白两个概念：**工作区 和 版本库（Repository）** 
工作区（Working Directory）：就是可以在电脑上看到的目录，比如我建的readme.txt文件，就是一个工作区

版本库（Repository）: 工作区有一个隐藏目录.git，这个不算工作区，而是Git的版本库。

Git的版本库里存了很多东西，其中最重要的就是称为stage（或者叫index）的暂存区，还有Git为我们自动创建的第一个分支master，以及指向master的一个指针叫HEAD。 
![![img](http://img.blog.csdn.net/20150712193401743)这里写图片描述](http://img.blog.csdn.net/20150712193401743) 

前面讲了**把文件往Git版本库里添加**的时候，是分**两步执行**的：

第一步是用git add把文件添加进去，实际上就是把文件修改添加到暂存区；

第二步是用git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支。


[Git 常用命令详解（二）](http://blog.csdn.net/ithomer/article/details/7529022)

[Git分支管理策略](http://www.ruanyifeng.com/blog/2012/07/git.html)

[Git 工作流程](http://www.ruanyifeng.com/blog/2015/12/git-workflow.html)

[Git远程操作详解](http://www.ruanyifeng.com/blog/2014/06/git_remote.html)