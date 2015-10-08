- 要用 git 管理某项目，需到其所在的目录，执行初始化：

			$ git init  
  - 更新git 
  
			$ git clone git://git.kernel.org/pub/scm/git/git.git
  - 从repohost克隆现有仓库到本地：
  
			$ git clone [URL]
			
  - 查看已克隆的仓库服务器名：git 默认`origin`

			$ git remote
指定`-v`显示名字对应的 URL
  - 查看本地仓库名：
  
			$ git branch
			* master
名字应该都是 URL 的代词
  - 发布文件到远程仓`git push [remote-name][branch-name]`

			$ git push origin master
  - 获取共享仓库的更新：

			$ git pull
