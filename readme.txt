这篇教程真不错https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/001374829472990293f16b45df14f35b94b3e8a026220c5000

查看公匙
$ cat ~/.ssh/id_rsa.pub


$ mkdir learngit
$ cd learngit
$ pwd
$ git init   //这时候会有一个隐藏目录.git创建在工作目录learngit下
创建readme.txg随便写点东西
$ git add readme.txt    //git add readme.txt有可能是提交所有文件
$ git commit -m "备注"
$ git status  //查看被改动的文件清单
$ git diff readme.txt   //修改详情
$ git add readme.txt  //再次添加修改后的文件
$ git log //查看版本库修改历史
$ git reset //hard HEAD^ 返回上一个版本 HEAD~100 返回n个版本
$ git reset //hard 1094a 返回某个特定版本，参数是id，可简写
$ git reflog  //查看所有命令
$ git checkout -- readme.txt //对工作区的文件修改进行撤销
$ git reset HEAD readme.txt //对缓冲区的文件修改进行撤销
$ rm test.txt //删除文件，手动删除也一样
$ git rm test.txt //删除后提交删除到缓冲区
$ git checkout -- test.txt //删错文件可以恢复
git remote add origin https://github.com/wangjian1984/HowToUseGit.git  //连接到github
$ git push -u origin master  //第一次提交代码
$ git push origin master //提交代码
git remote 查看远程分支
git remote -v 同上
--------------------------------------------------------
$ git branch dev 创建废纸dev
$ git checkout dev 切换分支
$ git branch 查看所有分支
$ git add readme.txt 在分支上提交
$ git commit -m "branch test"
$ git checkout master 切换回主线
$ git merge dev 合并分支内容
$ git branch -d dev 删除分支
cat readme.txt 主线与分支有冲突时比较
$ git checkout -b dev origin/dev 多人开发创建远程分支到本地,这个最好在看看教程