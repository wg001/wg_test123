1.关联远程仓库（参照http://www.cnblogs.com/hubcarl/p/4208144.html）
	1. git init
	2. git add .
	3. git commit -am "###"      -------以上3步只是本地提交
	4.git remote add origin git@xx.xx.xx.xx:repos/xxx/xxx/xxx.git
	5.git push origin 本地分支:远程分支
2.新建分支：
	1、Git  branch  test_fenzhi  添加分支
	2、git  checkout  test_fenzhi 切换到分支下面   就可以做一些操作了
	3、git push origin test_fenzhi   添加远程