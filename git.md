### （代码）版本控制工具
#### 分类
git  分布式
工作区
本地仓库
远程仓库
#### 安装 
mac 直接用
window 
下载安装  git brash
#### 参考资料
https://www.liaoxuefeng.com/wiki/896043488029600
#### github 码云
代码托管平台  
gitlab
svn  集中式
#### gitflow 的工作流
master 分支 线上分支
dev 分支 开发分支
bug 分支
项目创建 默认 master分支，主程切分一个dev分支
小组成员git clone 在dev分支上 切分自己的开发分支  项目开发
开发完成之后将自己分支合并到dev分支
将dev分支提交到线上的dev分支 push 之前先pull
将自己的分支删掉
在从div分支上复制一份出来
#### 基本命名
git  init  创建本地仓库
git remote add origin  url  将本地的仓库和远程仓库简历连接
git clone  url  克隆远程仓库代码 先有线上代码

git  status   查看当前的状态

git   add  文件名 （.） 将修改的文件放到暂存区

git   commit -m '注释'  将更改的文件进行提交

git push origin master 将本地仓库的代码提交到线上的master分支


git  reset  --hard  版本号    版本的回滚操作 向前  向后  版本id
git  log  --pretty=oneline  查看当前所有的版本号
git  reflog   查看所有的操作

git branch  查看所有的分支  * 当前分支
git checkout  分支名  切换分支
git checkout  -b 分支名  新建一个分支并且切换
git  merge  dev     当当前分支合并dev分支
git  branch -D  dev  删除某一分支
git  pull   拉取线上代码 将线上的master 分支 合并到本地的master

冲突的解决
1.冲突绝对不能出现在线上
2.提交之前一定要下拉 git  pull
3.有用留着没用的干掉


