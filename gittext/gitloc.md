git 本地操作：  

- clone远程库后，运行`git status`  
			
		Untracked files:
  			(use "git add <file>..." to include in what will be committed)

		gittext/

		nothing added to commit but untracked files present (use "git add" to track)


需要执行`add`，将文件纳入git管理（追踪）：  
			
			git add <fileName>  
			
此时，文件就处于staged状态了，git 提示`git rm --cached <file>`取消暂存操作；  
对文件夹里的md文件做了点修改后，再status下：  

			modified:   gittext (modified content)  

进入文件夹`add`已修改文件  

- 提交已修改文件

			git commit -m "test commit"  
只用`git commit`会进入vim编辑；那引号内部是什么，需要编辑？  
查看更新历史`git log`，显示了4项内容，第四项就是test commit，应该是对更新的简述说明  
现在工作目录clean，可以进行push了	  

- 