#### **git 基本操作**

	1. 初始化一个本地仓库			
		$git init					
	2. <br/>					
		$git add .					
		或者						
		$git add file1 file2
		$git commit -m '提交的log信息'	
	3. 关联到远程git仓库 （远程git仓库应该存在）					
		$git remote add origin https://github.com/Edjies/trygit.git	
	4. push 到远程git仓库											
		$git push -u origin master      # origin 表示远程仓库， master表示分支名	
	5. pull 同步远程git仓库									
		$git pull orgin master								
	6. 创建、切换一个分支 										
		$git branch branch1  # 现在仅在本地建立了一个分支	
		$git checkout branch1 # 切换到branch1分支			
		$git push origin branch1 #将本地分支提交到远程仓库	
	7. 删除一个分支											
		$git branch -d <分支名称> #删除本地分支				
		$git push origin :<分支名称> #删除远程分支			
	8. 分支合并												
		$git checkout <目标分支>							
		$git merge <分支名称>
	9. 查看, 同步分支


		
	9. 创建标签												
		$git tag -a <TAG 名称> -m 'tag log message'   #创建一个标签	
		$git push orgin --tags   #将标签提交到远程仓库

#### **git进阶知识**
     1.
     2.
     3.
     4.
     5. 

### **git ask**
	1. 为什么需要使用branch？										
		在不影响主分支的情况下， 进行新功能的开发					
	2. 为什么需要使用TAG?											
		保存稳定版本的代码											
	
	
	