# git命令
### git基本命令
#### 三个区域
* 工作区
* 暂存区
* 本地仓库
* 远程仓库(github,gitlab)
#### git init 
* 用来来初始化一个本地项目
* 把本地项目进行托管
##### 注意：需要在项目根目录，进行初始化
#### git add 
* 把工作区的代码提交到暂存区
* 用来对文件进行托管 
* git add [FileName] 
* git add . // 表示托管该项目所有文件
#### git commit -m 
* 把暂存区代码提交到本地仓库
* -m 加该此提交的说明
* git commit -m "说明"
#### git push
* 把本地仓库提交到远程仓库


### 常用命令
#### gitk
* 一个图形界面
* 查看每一次提交的信息

#### git log
* 查看说有commit信息

#### git reset --hard
* 从暂存区恢复到工作区


#### git checkout 
* 用来切换分支
* git checkout [branchName]

#### git brach 
* 查看分支

