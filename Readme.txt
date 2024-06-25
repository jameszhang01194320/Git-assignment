Homework for git assignment for week one
submitted on May 27, 2024

How to use Git to manage files

Use Git Base to do this work.

1. 
In intro_to_ct fold, create a folder named Git-assignment as repository
open Git-assignment use Git-Base
Initialize the repository: 
	git init

Adding Files to the folder
(I copy two files:MovieLightPlannerFlowchart2024.5.22.drawio.pdf and Readme.txt to this folder)
Use the git add command to Stage files for commit: 
	git add .

Commit staged files: 
	git commit -m "homework Git-assignment"

2.
Connecting to GitHub
Since I already create an account "d01194320" in Github,I don't need create a new one,
but the account is hard to understand, I change the user name to jameszhang01194320.

On github, create a new repository:Git-assignment, 
then clone the ssh link: Copy the repository URL: 

	git@github.com:jameszhang01194320/Git-assignment.git

3.
Back to my desktop, in Git Bash, use command to connect my local repository to the new GitHub repository:
	
	git remote add origin git@github.com:jameszhang01194320/Git-assignment.git

Push my local commits to GitHub: 

4. use git clone https://github.com/jameszhang01194320/Git-assignment.git

	git push origin master

Go to Github to find the pushed files,
copy the address:
	https://github.com/jameszhang01194320/Git-assignment.git
Submit the works.

update info:
git config --global user.name "jameszhang01194320"
git config --global user.email "你的新邮箱@example.com"

1. 清除 Git 缓存的旧凭证
在终端或命令提示符中运行以下命令：

记住:
git pull origin master --allow-unrelated-histories
打开“凭证管理器”（可以通过在开始菜单中搜索 Credential Manager 打开）。
选择“Windows 凭证”。
找到与 github.com 相关的条目，并将其删除。
