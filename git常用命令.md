# git常用命令
## 初始化仓库提交一次修改

### 在github中新建LearnGit仓库,不要初始化readme.然后连接至远程库
  
1. `C:\Users\bailong\Documents\LearnGit>git init` *初始化本地仓库*

2. `C:\Users\bailong\Documents\LearnGit\README.md` *新建文件*

3.  `>git add README.md` *README.md添加至暂存区*

4. `>git commit -m "first commit"` *将修改提交至HEAD*

5. `>git remote add origin git@github.com:XiaoNiFF/LearnGit.git` *将本地库与远程库连接*

### 本地修改readme,提交并同步至远程
  
1. `>git add *`

2. `>git commit -m "修改readme.md"`

3. `>git push origin master`

### 查看git日志

1. `>git log --pretty=oneline`


Commit ID | branch                          | Commit信息
:-:       | :-:                             | :-: 
3cadbb0   | (HEAD -> master, origin/master) | 修改readme.md 
bd5caab   |                                 | first commit 