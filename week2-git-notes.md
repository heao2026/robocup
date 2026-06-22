# 第二周Git学习笔记
## 一、基础提交命令
1. git add . ：将本地所有修改文件加入暂存区
2. git commit -m "提交描述" ：把暂存区内容保存到本地版本库
3. git push ：将本地版本上传推送到GitHub远程仓库
4. git pull ：拉取远程仓库最新代码到本地

## 二、分支操作
1. git branch ：查看本地所有分支
2. git branch 分支名 ：新建分支
3. git checkout 分支名 ：切换指定分支
4. git merge 分支名 ：将目标分支合并到当前分支

## 三、查看信息命令
1. git status ：查看当前文件修改、暂存状态
2. git log ：查看全部提交历史记录
3. git diff ：查看文件未暂存的修改细节

## 四、.gitignore作用
配置不需要Git追踪管理的文件，如缓存、依赖、密钥、系统临时文件，不会上传到远程仓库。

## 五、GitHub概念
1. Issues：问题反馈板块，用于提bug、需求讨论
2. Pull Request(PR)：向原仓库提交自己修改代码，等待作者审核合并
3. Fork：复制别人公开仓库到自己GitHub账号，可自由修改
