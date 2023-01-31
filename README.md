# git-guide

## 几个常用命令示意图

![image](https://user-images.githubusercontent.com/3445260/215679717-b3e2fd85-738d-436b-af40-701a38649aa5.png)


## git中一些专用名词

- Workspace：工作区
- Index / Stage：暂存区
- Repository：仓库区（或本地仓库）
- Remote：远程仓库

## 常用命令

```
# 在当前目录新建一个Git代码库
git init

# 新建一个目录，将其初始化为Git代码库
git init [目录名]

# 添加指定文件到暂存区
git add [file1] [file2] ...

# 添加指定目录到暂存区，包括子目录
$ git add [dir]

# 添加当前目录的所有文件到暂存区
$ git add .

# 添加每个变化前，都会要求确认
# 对于同一个文件的多处变化，可以实现分次提交
$ git add -p

# 删除工作区文件，并且将这次删除放入暂存区
$ git rm [file1] [file2] ...

# 停止追踪指定文件，但该文件会保留在工作区
$ git rm --cached [file]

# 改名文件，并且将这个改名放入暂存区
$ git mv [file-original] [file-renamed]

# 下载一个项目和它的整个代码历史
git clone [url]

# 表示将在工作空间但是不在暂存区的文件撤销更改
git restore 

# 作用是将暂存区的文件从暂存区撤出，但不会更改文件
git restore --staged
```

### 参考网址

https://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html
