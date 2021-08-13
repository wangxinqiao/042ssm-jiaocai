# ssm教材征订与发放管理系统
ssm教材征订与发放管理系统


#### 介绍
```
教材征订与发放管理系统。本系统共分三种角色，分别为管理员、老师、班长；现在分别来介绍各个角色的功能：  
```管理员```  
查看所有图书  
修改图书库存  
审批图书订单(通过图书订单,不通过订单)  
删除图书订单  
查看等待发放的图书  
查看已经发放的图书  
增加库存图书  
删除库存图书  
修改图书数量  
教师与班级管理  
查看教师列表  
查看班长列表  
修改教师信息  
修改班长信息  
修改班长密码  
修改教师密码  
删除教师  
删除班长  
发放图书  
修改教师信息  
修改学生信息  
查看已经发放订单  
  
```老师```  
查看自己订单  
查看图书信息  
增加订单  
查看发放订单  
修改个人信息  
修改学生  
查看班长列表  
修改班长信息  
  
```班长```  
修改个人信息  
查看自己班已经审批订单
```

源码获取：[ **点此获取** ](http://www.shuyue.fun/?type=productinfo&id=143)

#### 环境需要
```
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 否；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目 
6.数据库：MySql 5.7版本；
```

#### 技术栈
```
1. 后端：Spring SpringMVC MyBatis
2. 前端：JSP+jQuery
```

#### 使用说明
```
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中jdbc.properties配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入localhost:8080/xxx 登录
5. 管理员账户：admin  密码：123
6. 老师账户：111111  密码：123456
7. 班长账户：张三 密码：123
```

#### 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/215117_f034a94c_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/215210_43fd4b4e_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/215227_4c4cc89f_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/215242_21c86860_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/215255_167819ea_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/215307_086b1967_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0307/215321_160dcf61_863230.png "屏幕截图.png")
