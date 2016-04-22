git 基本操作</br>					<br/>
	1. 初始化一个本地仓库			<br/>
		$git init					<br/>
	2. 将  							<br/>					
		$git add .					<br/>
		或者						<br/>
		$git add file1, file2, ...		<br/>
		$git commit -m '提交的log信息'	<br/>
	3. 关联到远程git仓库 （远程git仓库应该存在）					<br/>
		$git remote add origin https://github.com/Edjies/trygit.git	<br/>
	
	4. push 到远程git仓库											<br/>
		$git push -u origin master      # origin 表示远程仓库， master表示分支名	<br/>
	
	5. pull 同步远程git仓库									<br/>
		$git pull orgin master								<br/>
	
	6. 创建一个分支 										<br/>
		$git branch branch1  # 现在仅在本地建立了一个分支	<br/>
		$git checkout branch1 # 切换到branch1分支			<br/>
		$git push origin branch1 #将本地分支提交到远程仓库	<br/>
	
	7. 删除一个分支											<br/>
		$git branch -d <分支名称> #删除本地分支				<br/>
		$git push origin :<分支名称> #删除远程分支			<br/>
	
	8. 分支合并												<br/>
		$git checkout <目标分支>							<br/>
		$git merge <分支名称>								<br/>
		
	9. 创建标签												<br/>
		$git tag -a <TAG 名称> -m 'tag log message'   #创建一个标签	<br/>
		$git push orgin --tags   #将标签提交到远程仓库				<br/>
		

git ask </br>
	1. 为什么需要使用branch？										<br/>
		在不影响主分支的情况下， 进行新功能的开发					<br/>
	2. 为什么需要使用TAG?											<br/>
		保存稳定版本的代码											<br/>
	
	
	