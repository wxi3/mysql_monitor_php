# mysql_monitor_php
基于原有的mysql_monitor项目进行的二次开发，更方便mysql的执行监控，提高代码审计效率
0.前言
因为Seay软件的mysql监控不知道什么原因一致用不了
而很多开源的项目都是java开发的
作者比较菜，jar文件打不开，不懂用（QAQ）
找了个php项目的，在原有的基础上新增了一些功能，以更方便进行SQL注入的代码审计



原作者代码链接：[mysql_monitor](https://github.com/amulx/mysql_monitor)


1.运行效果截图

![image](https://user-images.githubusercontent.com/98884431/235581026-19b8eeec-f030-4cae-86e0-eaae5539f565.png)





2.安装环境
基本的PHP运行环境（作者使用小皮）
![image](https://user-images.githubusercontent.com/98884431/235581946-0d0a51a3-2300-446f-aeeb-2b7249d88cb2.png)



3.二次开发变化
   #提供了除了默认端口外的其它端口的链接方式；
	 #提供了清除页面的按钮（原来的代码只能刷新页面重新链接才能清空页面）；
	 #保存默认的账号密码（原项目刷新一下就得重新输入账号密码）
	 
想要保存默认链接的账号密码得在mysql_audit.php里面修改value值，好吧没什么好说的OVO，作者太菜了，下次争取用java写一个
![image](https://user-images.githubusercontent.com/98884431/235582030-9854e567-d102-4c14-9a2e-d489f806d270.png)

	
	


