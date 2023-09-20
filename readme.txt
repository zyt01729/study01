步骤一：
 初始化本地仓库： git init
 1、将需要提交的文件提交到暂存区（追踪标记）: 
           git add readme.txt
 (使用git status 查看暂存区内容，此时暂存区文件变为绿色)
 2、提交并且备注:
           git commit -m "第一次提交"
 (使用git status 查看暂存区内容，此时暂存区文件变为红色)

步骤二：
 提交到远程仓库： 
          git remote add origin https://github.com/zyt01729/study01.git
          git push -u origin main
	  用户名为gitup用户名
	  密码为：token值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（30天有效）

   