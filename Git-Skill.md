###  上传项目到git系统
- 在git系统创建项目库
- 本地创建git本地库 
> git init

- 与远程git库建立连接 
> git remote add origin https://xxx.git

- 本地git库进行保存提交
>  git add .
git commit -m "Initial commit"

- Push到远程git库
> git push -u origin master

### 更新项目到git系统
> git push -u origin master

### 拉取git系统的项目
> git pull

### 合并本地和远程git
> git pull --rebase origin master

### Clone远程库到本地
> git clone https://xxx.git
Git pull origin master
