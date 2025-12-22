一、Git 基础知识（git-basics.md）
1. Git 的基本概念

Git 是一个分布式版本控制系统，主要用于管理源代码和文档的版本变化。
它可以帮助开发者记录每一次修改，并支持多人同时协作开发。

Git 的几个核心概念包括：

仓库（Repository）：用于存放项目代码和历史记录

提交（Commit）：一次代码或文件修改的记录

分支（Branch）：用于在不影响主代码的情况下进行开发

远程仓库（Remote）：托管在 GitHub、Gitee 等平台上的仓库

2. 常用命令说明

在项目开发过程中，常用的 Git 命令包括：

git clone <仓库地址>      # 克隆远程仓库到本地
git status                # 查看当前仓库状态
git add .                 # 添加修改内容到暂存区
git commit -m "message"   # 提交修改
git push                  # 推送本地提交到远程仓库
git pull                  # 拉取远程最新代码


这些命令构成了日常 Git 使用的基本流程。