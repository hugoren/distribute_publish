# distribute_publish

#版本
软件/模块	     版本	          备注
python	      2.7.10	 
paramiko	    1.16.0	        用于ssh链接服务器
progressbar	  2.3-py2.7	     google的一个进度条python模块

#程序结构
本程序由4-5个目录构成（bin、conf、log、script、dist、build）:    
###bin：存放了主程序文件。   
###conf：存放了配置文件。     
###log：存放了运行过程中的日志文件。有两种日志文件一个是自己记录的log，还有一个是paramiko模块记录的exec_cmd_xx.log）。   ###script：存放了执行远程服务器shell的命令文件（有两个一个是为了停止服务cmd，另一个是启动服务stop_server.cmd）。    ###dist：如果是使用exe版就存在此目录 -> 存放执行主程序。
###build：如果是使用exe版就存在此目录 -> 存放python编译后的文件。


#程序流程图

![alt text](http://dl2.iteye.com/upload/attachment/0116/4532/3b1e36a0-32fb-3394-83ea-58f208c6acae.png)
