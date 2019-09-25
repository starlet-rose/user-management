# user-management


ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'ljs2455009782@'      改myqky密码，注：后面加；号

在忘记根密码的时候，可以这样

以窗为例：

关闭正在运行的MySQL的服务。

打开DOS窗口，转到MySQL的\ BIN目录。

--skip-grant-tables的意思是启动MySQL服务的时候跳过权限表认证。

再开一个DOS窗口（因为刚才那个DOS窗口已经不能动了），转到mysql的\ BIN目录。

输入mysql回车，如果成功，将出现MySQL域名>。

连接权限数据库：。

改密码：更新用户设置的密码= password（“ 123”）其中user =“ root”;（别忘了最后加分号）。

刷新权限（必须步骤）：flush privileges; 。

退出退出。

注销系统，再进入，使用用户名根和刚才设置的新密码123登录。
