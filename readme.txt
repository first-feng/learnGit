第一步 添加了readme.txt文件
第二步 用于查看diff命令的作用
第三步 通过checkout命令可以使工作区的文件和版本库中文件保持同步，如果文件已经加入到暂存区，先用git reset --HEAD filename，使文件在暂存区撤销，然后在使用checkout，保持同步，
第四步 通过分支来修改文件。创建分支的命令 git checkout -b branchName ； 前面命令包含创建和切换到分支两步。相当于git branch branchName，git checkout branchName。