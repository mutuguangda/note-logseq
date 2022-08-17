- 一句话：git pull
- 安全流程
- ```
  git status 查看本地分支文件信息
  git checkout [file name] 若文件有修改，可以还原到最初状态。若文件需要更新到服务器上，应该先 merge 到服务器，再更新到本地
  git branch 查看当前分支情况
  git checkout remote branch 若分支为本地分支，则需切换到服务器的远程分支
  git pull
  ```