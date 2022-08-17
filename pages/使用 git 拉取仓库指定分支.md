- 在本地建立 [[git]] 仓库，然乎下载指定分支仓库，最后创建本地分支关联指定远程分支。
- ```
  mkdir repo
  cd repo
  git init
  git remote add <your_repo_url>
  git fetch origin dev
  git checkout -b dev origin/dev
  ```