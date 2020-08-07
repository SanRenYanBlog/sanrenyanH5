## 项目说明文档
## git init
- 把当前项目初始化为版本库
- 当前目录下会生成一个隐藏文件.git

## git add 文件名
- 把当前文件发送到暂存区
- git add readme.med 把这个文件提交到暂存区
- git add . 当前目录所有变动提交到暂存区

## git status
- 查看当前目录状态

## git commit -m '提交的注释文本'
- 把暂存区的内容提交到本地仓库

## 本地仓库的三个组成部分
- 工作区：实际持有文件的
- 暂存区
- 本地仓库

## git log
- 查看操作日志

## git reflog
- 查看简版日志

## git diff [文件名]
- 查看文件变更信息

## git reset --hard [版本号] 
- 回退到指定版本

## git reset --hard^
- 回退到上个版本
- git reset --hard^^回退到上上个版本

# 远程仓库

## remote add origin 仓库地址
- 把本地仓库与远程仓库关联

## git remote -v
- 查看本地仓库关联的远程仓库地址

## git push -u origin master
- git push 本地仓库提交到远程仓库
- -u origin master 设置默认远程仓库或分支
- 执行完这个命令之后，以后可以直接git push提交到远程仓库的master分支

# 更新代码
 把远程代码更新到本地时，一定要养成先提交本地代码，再更新

## git pull
- 把远程的代码拉取到本地

## git fetch
- 从远程获取到本地，不会自动marge

## git clone [地址]

- 将远程仓库克隆到本地

# 分支操作


