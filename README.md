git 基本操作</br>
	1. 初始化一个本地仓库
		$git init
	2. 将  </br>
		$git add .
		或者</br>
		$git add file1, file2, ...
		$git commit -m '提交的log信息'
	3. 关联到远程git仓库 （远程git仓库应该存在）
		$git remote add origin https://github.com/Edjies/trygit.git
	
	4. push 到远程git仓库
		$git push -u origin master      # origin 表示远程仓库， master表示分支名
	
	5. pull 同步远程git仓库
		$git pull orgin master
	
	6. 创建一个分支 
		$git branch branch1  # 现在仅在本地建立了一个分支
		$git checkout branch1 # 切换到branch1分支
		$git push origin branch1 #将本地分支提交到远程仓库
	
	7. 删除一个分支
		$git branch -d <分支名称> #删除本地分支
		$git push origin :<分支名称> #删除远程分支
	
	8. 分支合并
		$git checkout <目标分支>
		$git merge <分支名称>
		
	9. 
		

git ask </br>
	0. 为什么使用git?</br>
	1. 为什么需要使用branch？</br>
	2. 为什么需要使用TAG?</br>
	
	
	