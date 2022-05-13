## Git配置命令
- 配置用户名：git config --global user.name "your name"
- 配置用户邮箱: git config --global user.email "your email"
## Git工作区操作命令
### 提交
- 提交工作区所有文件到暂存区: `git add .`
- 提交工作区中指定文件到暂存区: `git add <file1> <file2> ...`
- 提交工作区中某个文件夹中所有文件到暂存区: `git add [dir]`
### 撤销
- 撤销commit: `git rm --cached <file>`
## 暂存区上的操作命令
- 修改提交的注释：`git commit --amend`
