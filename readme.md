## 项目说明文档
---

```html
<html>
    <body>
        <p>这是一个代码块！</p>
    </body>
</html>
```
## git init
1. 把当前项目初始化为版本库
2. 当前目录下会生成一个隐藏文件.git

## git add 文件名
1. 把当前文件发送到暂存区
2. git add readme.med 把这个文件提交到暂存区
3. git add . 当前目录所有变动提交到暂存区

## git status
1. 查看当前目录状态

## git commit -m '提交的注释文本'
1. 把暂存区的内容提交到本地仓库

## 本地仓库的三个组成部分
1. 工作区：实际持有文件的
2. 暂存区
3. 本地仓库

## git log
1. 查看操作日志

## git reflog
1. 查看简单版日志

## git diff [文件名]
1. 查看文件变更信息

## git reset --hard [版本号] 
1. 回退到指定版本

## git reset --hard^
1. 回退到上个版本
2. git reset --hard^^回退到上上个版本

# 远程仓库

##remote add origin 仓库地址
1. 把本地仓库与远程仓库关联

