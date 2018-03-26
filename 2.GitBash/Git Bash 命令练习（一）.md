# Git Bash 命令练习(一)
## 1.新建代码仓库类
- 在当前目录新建一个Git代码库  
```
git init
```
- 下载一个项目和它的整个代码历史
```
“url格式：http://github.com/[userName]/reposName”
git clone [url]
```

## 2.添加删除文件
- 添加指定文件到暂存区  
```
git add [file1] [file2]
```
- 删除工作区文件，并且将这次删除放入暂存区
```
git rm [file1] [file2]
```
- 改名文件，并且将这个改名放入暂存区
```
git mv [file-origin] [file-renamed]
```

## 3.代码提交
- 提交暂存区到仓库
```
git commit -m [message]
```
- 直接从工作区提交到仓库  
前提该文件已经有仓库中的历史版本
```
git commit -a -m [message]
```

## 4.查看信息
- 显示变更信息
```
git status
```
- 显示当前分支的历史版本
```
git log  
git log --oneline
```

